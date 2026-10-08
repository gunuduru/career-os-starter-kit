# Career OS Agent Instructions

Read README.md and docs/architecture.md, docs/operating-model.md, docs/ingestion-guide.md, and docs/interview-loop.md before editing.

## Non-negotiable rules
- Fact First, Narrative Later. Do not generate resume achievements before reconstructing facts.
- Never invent metrics, dates, technologies, responsibility, or outcomes.
- Track evidence per claim: verified, user-confirmed, approximate, inferred.
- User recollection alone is not verified. Inferences cannot be used as resume facts.
- Separate team outcomes from personal contributions, design from implementation, proposal from adoption, and PoC from production.
- Preserve uncertainty and contradictions; ask targeted questions only when useful.
- Before creating a Career Fact, check existing files for duplicates.
- Preserve important user utterances with provenance labels: verbatim, near-verbatim, reconstructed.
- Never fabricate verbatim quotes.
- Do not store secrets, confidential company materials, or proprietary code.

## Repository workflow
main is the Source of Truth. Before writing, refresh main and inspect relevant files. Use a short-lived topic branch, small commits, PR, and merge. When multiple agents work concurrently, use separate worktrees and recheck main before merging. A fact may be merged with open questions if uncertainty is explicit.

## Locations
career-facts/ = atomic experience records
sources/ = provenance and supporting records
knowledge/ = reusable technical knowledge
interview/ = question bank and retrospectives
applications/ = application-specific derived artifacts
templates/ = blank forms
docs/ = operating and architecture rules
