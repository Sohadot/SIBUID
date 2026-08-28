# Source Register

**Reference date:** 2026-08-28

Primary sources used only for time-bound landscape/history claims. They do not define SIBUID.

| ID | Source | Role | URL |
|---|---|---|---|
| SRC-001 | SPIFFE Concepts | Workload identity and SPIFFE ID context | https://spiffe.io/docs/latest/spiffe/concepts/ |
| SRC-002 | RFC 9334 | RATS architecture; Evidence, Verifier, Attestation Result | https://www.rfc-editor.org/rfc/rfc9334.html |
| SRC-003 | in-toto Statement v1 | Artifact subject and digest semantics | https://github.com/in-toto/attestation/blob/main/spec/v1/statement.md |
| SRC-004 | RFC 9943 | SCITT Subject, statement sequencing, transparency architecture | https://www.rfc-editor.org/rfc/rfc9943.html |
| SRC-005 | Sigstore Rekor | Transparency-log role and append-only signed metadata | https://docs.sigstore.dev/logging/overview/ |
| SRC-006 | draft-klrc-aiagent-auth-03 | 2026 AI-agent authentication/authorization context | https://datatracker.ietf.org/doc/draft-klrc-aiagent-auth/ |

## Admission rule

Canonical conceptual claims must not depend on a time-bound standard. Named standards belong in `/landscape/` or `/history/` unless required to correct a factual misconception.
