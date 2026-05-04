# tuiplexity — Agent Workflow Contract
Version: 1.0 | Updated: 2026-05-04
Status: Stub — pending definition or consolidation into monorepo

## Entry Point
1. Read CLAUDE.md (if present)
2. Read HANDOFF.md (if present) — VERIFY claims before acting
3. Read this file
4. Read https://github.com/thelaunchpadtlp/universe-infrastructure/blob/main/SINGULARITY_PLAN.md

## Stack
Status: Stub repository (README only, 0 KB content). This concept has evolved into Terminal Quest at `github:thelaunchpadtlp/terminal-quest`. Retained for namespace/redirect purposes.

## Agent Roles
- **Orchestrator (Claude Code):** Architecture decisions, multi-file changes, planning
- **Executor (Codex):** Single-file implementations, refactors, code generation
- **Reviewer (Gemini):** PR review, test coverage, security audit
- **Auditor:** Companion to every non-trivial agent run

## Active Plans
| Plan | Location | Status |
|------|----------|--------|
| Grand Unification — GitHub Singularity | [SINGULARITY_PLAN.md](https://github.com/thelaunchpadtlp/universe-infrastructure/blob/main/SINGULARITY_PLAN.md#phase-4-github-singularity) | PENDING — awaiting Phase 3 (GCP) |
| Concept Successor | [terminal-quest](https://github.com/thelaunchpadtlp/terminal-quest) | ACTIVE — all new work goes there |

## Coding Standards
This repo is a stub. All active development has moved to `terminal-quest`. Do not add new code here.

## Deploy Protocol
No deployment. Stub repository retained for historical reference.

## Verification
- Check CI status: `gh run list --repo thelaunchpadtlp/tuiplexity --limit 3`
