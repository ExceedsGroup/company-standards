# Engineering Standards

## Documentation-First
- Significant changes require updated documentation in the same pull request
- Design intent, constraints, and operational impact must be recorded
- Ambiguity should be resolved with explicit acceptance criteria

## CI/CD Expectations
- All repositories must use automated checks before merge
- Required checks include build, test, and policy compliance where applicable
- Deployment processes must be scriptable and auditable

## Reproducibility Principles
- Build and test procedures must be deterministic
- Toolchain versions should be pinned or constrained
- Local and CI execution should produce consistent outcomes

## Pull Request Quality Bar
- Problem statement and scope are clear
- Tests are added or updated for behavior changes
- Backward compatibility impact is stated
- Documentation changes are included when policy, behavior, or usage changes
- Reviewer can validate change intent from PR description alone
