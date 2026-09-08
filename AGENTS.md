# Agent Briefing: openclaw-to-hermes-orchestrator-migration

## 1. Repository Overview & Purpose
- **Repository**: `webdev0814/openclaw-to-hermes-orchestrator-migration`
- **Visibility**: `Public`
- **Default Branch**: `main`
- **Last Updated / Pushed**: 2026-09-04
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
- `[f2aa3d6]` (2026-09-04) docs: add comprehensive agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[19a865d]` (2026-09-04) docs: add comprehensive agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[103f88b]` (2026-09-04) docs: add comprehensive agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[5e39aac]` (2026-09-04) docs: add comprehensive agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[cb4d901]` (2026-09-04) docs: add comprehensive agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[d109b3e]` (2026-09-04) docs: add comprehensive agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[992769b]` (2026-05-15) Add MIT license
- `[47aa355]` (2026-05-15) Add sanitized orchestrator transfer runbook

---

## 5. Current State & Immediate Next Steps
- **Current State**: Project is active under branch `main`.
- **When picking up this repo**:
  1. Inspect the top-level files and recent commits to understand the active feature or bugfix context.
  2. Verify all required credentials and environment variables before running integration scripts.
  3. Ensure all tests and linting pass after making modifications.
  4. Follow the repository conventions and preserve existing architecture patterns.

---

## 6. Agent Working Guidelines & Gotchas
- **Cross-Platform Compatibility**: Code may run across Windows, macOS, or Linux agent environments. Ensure path manipulations use OS-agnostic methods (e.g. `pathlib.Path` or `path.join`).
- **Secret Hygiene**: NEVER commit plain-text API keys, tokens, or credentials into repository files.
- **Git Commit Etiquette**: Use concise, conventional commit messages (e.g., `feat:`, `fix:`, `docs:`, `refactor:`).
- **Tooling Compatibility**: This briefing is kept aligned for Antigravity (`GEMINI.md`), Claude Code / Codex (`CLAUDE.md`), and general autonomous agents (`AGENTS.md`).
