# Career OS Starter Kit

A privacy-conscious, Git-based personal career knowledge system for Claude Code, ChatGPT, and other AI coding assistants.

**Fact First, Narrative Later.** Capture evidence-backed experiences before generating resumes, portfolios, or interview answers.

## Quick start

1. Click **Use this template** (if enabled) or fork/download this repository.
2. Create a **private** repository for your own career information. This public repository contains only generic scaffolding.
3. Open your private copy in Claude Code or another agent with repository access.
4. Paste [BOOTSTRAP_PROMPT.md](BOOTSTRAP_PROMPT.md) into your assistant.
5. Tell the assistant your target roles and describe your first experience in your own words.

For ChatGPT without repository access, upload the files or provide them as project context. The assistant should prepare changes for review instead of claiming to have committed them.

## What is included?

- [AGENTS.md](AGENTS.md): common instructions for AI agents
- [CLAUDE.md](CLAUDE.md): Claude Code entry point
- [docs/architecture.md](docs/architecture.md): data model and evidence levels
- [docs/operating-model.md](docs/operating-model.md): Git and collaboration workflow
- [docs/ingestion-guide.md](docs/ingestion-guide.md): reconstructing experiences from conversations
- [docs/interview-loop.md](docs/interview-loop.md): interview feedback loop
- [templates/](templates/): blank Career Fact, Source, Knowledge, Interview, and Application records

## Evidence policy

Claims are individually labeled `verified`, `user-confirmed`, `approximate`, or `inferred`. Never turn an inference into a resume fact. Separate personal ownership from team outcomes and implemented work from plans.

## Privacy and security

This repository deliberately contains no personal career records, company documents, proprietary source code, credentials, or real incident details. **Do not commit private career data to a public fork.** Use a private repository and review every proposed change before publishing. Git history retains deleted secrets: prevention matters more than cleanup.

## Repository structure

```text
career-facts/    Canonical atomic experiences
sources/         Evidence and provenance
knowledge/       Technical concepts
interview/       Interview question bank
applications/    Application tracking
templates/       Blank records
docs/            Architecture and operating rules
```

## Scope

This is a reusable starter scaffold, not an automated application service. Agents require the appropriate repository permissions to create branches, PRs, and commits. Customize role lenses and application criteria for your own career.
