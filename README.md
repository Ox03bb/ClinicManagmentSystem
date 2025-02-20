# ClinicManagmentSystem

## Branching Convention
We follow a branching convention to manage our codebase effectively. The convention is as follows:

- `main`: The main branch that represents the production-ready code. 
- `dev`: The development branch where new features are integrated and tested.
- `frontend` : The development branch for the frontend team .
- `backend` : The development backend for the frontend team .
- `feature/[b/f]-your-feature`: Branches  for developing new features. ex: `feature/f-leaderboard-points`
- `bugfix/[b/f]-your-bugfix`: Branches  for fixing bugs. ex: `bugfix/b-upload-file`
- `refactor/[b/f]-your-refactor`: Branches for refactoring existing code to improve readability, maintainability, or performance.Ex:`refactor/b-database-optimization`
- `conf/[b/f]-your-conf`: Branches  for conficurations . `conf/b-django-chanels`
- `hotfix/[b/f]-your-hotfix`: Branches created for critical bug fixes in the production code. These branches are created from the `main` branch and merged back into it once the hotfix is complete.

## Commit Message Structure
All commit messages should follow the format:
`Action | Content`
Where:
- **Action:** Describes what the commit does (e.g., Add, Fix, Update, Remove, Refactor, Configure, Hotfix, etc.).
- **Content:** A brief description of what was changed.
- 
### Examples:
- `Fix | Authentication problem`
- `Add | User profile page`
- `Refactor | Database query optimization`

> [!TIP]
> When creating a new branch, make sure to give it a descriptive name that reflects the purpose of the branch. For example, if you are working on a feature to add user authentication, you can create a branch named `feature/b-user-authentication`.

It is important to follow this branching convention to ensure a smooth and organized development process. By using separate branches for different features and bug fixes, we can easily track changes, collaborate effectively, and maintain a stable codebase.
