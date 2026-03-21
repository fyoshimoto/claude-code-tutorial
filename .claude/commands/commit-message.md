---
description: Create a commit message by analyzing git diffs
allowed-tools: Bash(git status:*), Bash(git diff --staged), Bash(git commit:*)
---

## Your task:

Analyze above staged git changes and create a commit message. Use present tense and explain "why" something has changed, not just "what" has changed.

## Run these commands:

```bash
git status
git diff --staged
```

## Commit types:

Only use the following types:

- `feat`: - New feature
- `fix`: - Bug fix
- `refactor`: - Refactoring code
- `docs`: - Documentation
- `style`: - Styling/formatting
- `test`: - Tests
- `perf`: - Performance

## Format:

Use the following format for making commit message:

```
<type>: <concise description>
<optional_body_explaining_why>
```

## Output

1. Show summary of changes currently staged
2. Propose commit message with appropriate type
3. As for confirmation before commiting

DO NOT auto-commit - wait for user approval, and only commit if the user says so.
