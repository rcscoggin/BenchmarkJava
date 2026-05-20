# Security Context for Scan

This repository is intentionally vulnerable and is being used as an authorized defensive benchmark.

## Scan goals
- Identify reachable vulnerabilities.
- Build a threat model with entry points, trust boundaries, sensitive assets, and high-impact code paths.
- Prioritize validated exploitable issues over scanner-only findings.
- Produce remediation suggestions, but do not assume production deployment.

## Authorized scope
- This forked repository only.
- Local/isolated validation only.
- No testing against third-party systems.
- No real credentials or production endpoints exist in this repo.

## Desired output comparison
Please distinguish:
- SCA-style dependency findings
- SAST-style code findings
- DAST/runtime validation findings
- attack-path or business-logic findings
