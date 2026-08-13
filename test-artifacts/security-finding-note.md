# Security / code-quality finding note (tool isolation)

Date: 2026-08-13
Repo: sperez-source/pbuild813

## Repo-level alerts (queried)

| Source | Result |
|--------|--------|
| Code scanning | No analysis found (404) |
| Dependabot | Disabled for this repository (403) |
| Secret scanning | No open alerts |
| Code quality finding #1 | Resource not accessible by integration (403) |

## Global security advisory sample

Referenced finding (GitHub Advisory Database):

- **GHSA-rm43-82j9-r4mj**
- Severity: high
- Summary: atomic-agents-stack dashboard path traversal (CWE-22)
- URL: https://github.com/advisories/GHSA-rm43-82j9-r4mj
- Vulnerable: `atomic-agents-stack` pip `<= 1.0.0` (patched in `1.1.0`)

## Code quality

GitHub Code Quality finding API was not accessible for this repo (403).
This PR documents that gap for isolation testing; no product code change intended.

Safe to close after the test run.
