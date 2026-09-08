# Agent Briefing: openclaw-to-hermes-orchestrator-migration

## 1. Repository Overview & Purpose
- **Repository**: `webdev0814/openclaw-to-hermes-orchestrator-migration`
- **Visibility**: `Public`
- **Default Branch**: `main`
- **Last Updated / Pushed**: 2026-09-08
- **Description**: orchestrator transfer: OpenClaw to Hermes
- **Context from README**: A staged, rollback-safe runbook for transferring operational orchestration from an OpenClaw-facing assistant (FACE) to a Hermes operational brain (BRAIN), while keeping user-facing channels stable. This repository is a sanitized operational pattern. Do not commit bot tokens, HMAC secrets, private SS...


---

## 2. Tech Stack & Architecture
- **Primary Language / Ecosystem**: General / Multi-language
- **Key Directories**: Single root directory structure.
- **Notable Top-Level Files**: `.gitignore`, `AGENTS.md`, `CLAUDE.md`, `GEMINI.md`, `LICENSE`, `README.md`, `RUNBOOK.md`, `SKILL.md`

---

## 3. Setup & Execution Commands
### Environment Setup & Installation
```bash
# Review repository files and install dependencies corresponding to the language/runtime.
```

### Running / Starting
```bash
# Check main entry point scripts or config files.
```

### Testing / Verification
```bash
# Run relevant unit/integration tests (e.g. pytest or npm test)
```

---

## 4. Recent Commit Activity (Where We Left Off)
The most recent commits show the latest development trajectory:
- `[74896e0]` (2026-09-08) docs: update agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[afb3ec4]` (2026-09-08) docs: update agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[c517003]` (2026-09-08) docs: update agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[8f23d6c]` (2026-09-08) docs: update agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[d934a16]` (2026-09-08) docs: update agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[1c9eef6]` (2026-09-08) docs: update agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[d01167a]` (2026-09-08) docs: update agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[3cac9a5]` (2026-09-08) docs: update agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[a8a5721]` (2026-09-08) docs: update agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[c7812fe]` (2026-09-08) docs: update agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)

---

## 5. Current State & Immediate Next Steps
- **Current State**: Project is active under branch `main`.
- **When picking up this repo**:
  1. Inspect the top-level files and recent commits to understand the active feature or bugfix context.
  2. Verify all required credentials and environment variables before running integration scripts.
  3. Ensure all tests and linting pass after making modifications.
  4. Follow the repository conventions and preserve existing architecture patterns.

---

## 6. Multi-Computer Handoff & Git Sync Protocol
- **On Session Start**: Always run `git pull` when opening this repository on any computer to synchronize the latest changes.
- **On Task Completion**: Before ending any agent session, the agent **MUST**:
  1. Update Section 5 (Current State & Next Steps) in this `AGENTS.md` file.
  2. Stage all modifications (`git add .`).
  3. Commit with a concise conventional message (`git commit -m "feat/fix: ..."`).
  4. Push directly to GitHub (`git push`).
- **Secret Hygiene**: NEVER commit plain-text API keys, tokens, or credentials into repository files.
