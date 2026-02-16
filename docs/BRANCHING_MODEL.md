# Branching Model

## Main Branch Policy
- `main` is the protected integration branch
- Direct pushes to `main` are not allowed
- Changes enter `main` only through reviewed pull requests

## Branch Naming
Use lowercase, hyphen-separated names with a short scope descriptor:
- `feature/<topic>`
- `fix/<topic>`
- `chore/<topic>`

Examples:
- `feature/release-template-standardization`
- `fix/versioning-guidance-ambiguity`
- `chore/repository-housekeeping`

## Pull Request Requirements
- At least one reviewer approval
- All required checks pass
- No unresolved review comments
- PR description includes summary, impact, and any follow-up actions
