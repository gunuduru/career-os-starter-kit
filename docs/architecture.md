# Architecture

**Fact First, Narrative Later.** Career Facts are canonical; resumes and interview answers are derived views.

## Entities
- Career Fact (`cf-`): atomic work experience and claim-level evidence
- Source (`src-`): provenance (document, code, recollection)
- Technical Knowledge (`tk-`): independent concepts to learn
- Interview Question (`iq-`): general, career-derived, or actual
- Application (`app-`): one employer/role and its process

Source -> Career Fact -> Application -> Resume / Interview Answer
Technical Knowledge and Interview Questions link to Career Facts.

## Evidence levels
- `verified`: corroborated by primary evidence such as documents, code, or metrics
- `user-confirmed`: user's clear recollection, not independently verified
- `approximate`: rough estimate or uncertain date/number
- `inferred`: agent interpretation; never a resume fact without confirmation

Assign evidence per claim, not per file. Unknown stays unknown. Keep individual contribution separate from team result, proposal from implementation, and correlation from causation.

Use stable, lowercase kebab-case IDs. Never silently overwrite conflicting claims.
