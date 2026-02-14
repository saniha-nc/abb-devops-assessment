Branching Strategy Used:

1. main branch
- Production code
- Protected branch
- No direct commits allowed

2. dev branch
- Integration branch
- All features merged here first

3. feature branches
- Created from dev
- Example: feature/login

4. release branch
- Used for release preparation
- Example: release/v1

Workflow:
feature → dev → main
Pull request mandatory before merge.
