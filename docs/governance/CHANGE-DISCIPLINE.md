\# Change Discipline (Kernel Next)



This document defines how change is permitted during the kernel-next phase.



The purpose is to preserve intent, prevent drift, and ensure every change

remains understandable and reviewable.



---



\## Principles



\- Changes are deliberate

\- Changes are documented

\- Changes are reversible

\- Changes assume public visibility



---



\## What Requires a Commit



Every change, regardless of size, requires:

\- A clear commit message

\- A readable diff

\- No bundled or unrelated edits



---



\## What Is Not Allowed



\- Silent changes

\- Bulk refactors

\- Cosmetic churn

\- Tool-driven rewrites



If a change cannot be explained in plain language, it does not belong here.



---



\## Review Posture



This repository must always be in a state suitable for:

\- External review

\- Regulatory inspection

\- Public scrutiny



---



End of document.



