# SIBUID Decision Log

## DEC-001 — Semantic Positioning and Reference Scope

**Date:** 2026-08-28  
**Status:** Binding for Reference v0.1

### Decision

`SIBUID` expands to **Software Identity Binding Unique Identifier**.

SIBUID is positioned as a **descriptive semantic term**, not as a claim of a new Internet protocol, standards-track identifier, credential format, registry, or trust architecture.

Canonical definition:

> A SIBUID is a unique identifier used to distinguish a defined software-identity binding within the continuity boundary established by a system's policy.

### Boundaries

- The software actor identity is distinct from the binding that gives the identity operational meaning.
- A binding identifier is distinct from an exact snapshot, digest, statement, attestation, or evidence-object identifier.
- A SIBUID identifies a binding **as delimited by a continuity policy**.
- Whether a SIBUID persists across a transition is therefore a policy decision.
- The reference does not impose one universal continuity policy.
- Existing standards and implementations are examples and evidence, not the definition of SIBUID.

### Durability rule

The durable problem belongs in canonical pages. Time-bound standards and implementations belong in landscape/history context and may be updated without redefining the term.

### Versioning

Material semantic changes require a new definition version and dated decision record. Editorial corrections may update `dateModified` without changing the definition version.
