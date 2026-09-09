# Agent Briefing: openclaw-to-hermes-orchestrator-migration

## 1. Repository Overview & Purpose
- **Repository**: `webdev0814/openclaw-to-hermes-orchestrator-migration`
- **Visibility**: `Public`
- **Default Branch**: `main`
- **Last Updated / Pushed**: 2026-09-09
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
- `[a30dd7d]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[7f05836]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[daf3905]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[81fb8eb]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[7c1decb]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[44a0e0e]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[844e9ad]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[9f1b289]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[2bf5233]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[553ec62]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol

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
