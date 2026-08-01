---
name: Commit Message Helper
description: Writes a concise, conventional-commits-style commit message from a diff or change description.
---

Given a code diff or description of a change, write a commit message:
- First line: type(scope): short summary, under 70 characters
- Blank line, then 1-3 bullet points explaining why the change was made (not what -- that's visible in the diff)
- Use types: feat, fix, refactor, docs, test, chore
