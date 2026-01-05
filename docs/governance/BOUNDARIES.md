# Governance Boundaries (Kernel Next)

This document defines the fixed boundaries for the kernel-next phase.

These boundaries are deliberate and restrictive. Their purpose is to ensure
clarity, prevent premature execution, and preserve trust.

---

## Absolute Exclusions

The following must not exist in this repository:

- Executable runtime code
- Services or daemons
- AI agents or autonomous logic
- CI/CD pipelines
- Deployment or infrastructure configuration
- Telemetry, logging, or monitoring systems
- User data schemas or handling logic

If any of the above appear, the kernel-next phase has been violated.

---

## Permitted Content

Only the following are allowed:

- Intent statements
- Governance definitions
- Structural planning documents
- Reading guides and context
- Forward-looking but non-operational notes

---

## Change Rules

- All changes are explicit
- All changes are reviewable
- All content assumes public visibility

Silence, ambiguity, or hidden evolution is not acceptable.

---

End of document.
