# PR & Learning Log Instructions

For every task, branch, or Pull Request you create:

1. Create a dedicated folder:
   - Path: `.antigravity/runs/pr-<task-name>/`
   - Never overwrite previous run folders.

2. Inside that folder, create exactly one file:
   - File: `AUDIT_LOG.md`

3. The file must include:
   - **What was changed:** Summary of files and logic modified.
   - **Root Cause Analysis:** Why the issue existed in the original code, citing specific lines.
   - **Remediation & Prevention:** Why this fix works and how to prevent this bug in the future.
   - **Blockers:** If anything failed or couldn't be fixed, explain why and what was attempted.
