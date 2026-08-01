---
name: Code Review Checklist
description: Runs a structured review pass over a code change looking for common issues.
---
Check the change for:
- Off-by-one errors and boundary conditions
- Missing error handling on external calls (network, filesystem, DB)
- Naming that doesn't match what the code actually does
- Dead code or leftover debug statements

Report findings as a short list, most important first. Don't nitpick style if there's a linter already enforcing it.

<!-- edited via real browser UI test -->
