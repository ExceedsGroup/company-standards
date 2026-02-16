# Security Baseline

## Mandatory Controls
The following controls are required for repositories governed by Exceeds Group standards:
- Dependabot (or equivalent dependency update automation) is enabled when dependency manifests are present
- Secret scanning is enabled
- Two-factor authentication (2FA) is required for organization members
- Least privilege access is enforced for all repositories and environments

## Access and Privilege
- Grant only the minimum permissions required to perform a role
- Review elevated access periodically and remove stale permissions
- Prefer role-based groups over direct individual privilege assignment

## Incident Handling Process
1. Detect and triage the reported issue.
2. Contain impact and preserve relevant evidence.
3. Remediate root cause and affected assets.
4. Communicate impact and status to appropriate stakeholders.
5. Complete post-incident review with corrective actions.

## Baseline Review
- Review this baseline at least quarterly
- Update controls based on risk, tooling changes, and audit findings
