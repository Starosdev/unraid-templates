# Repository Guidelines

<!-- staros-agents-baseline: Staros-Labs/infra AGENTS.md -->

This repository adopts the Staros org agent baseline by reference. The
baseline rules (git worktrees, session-start sync, model selection, handoff
checkpoints, communication, session closeout) live in `Staros-Labs/infra`
`AGENTS.md` and apply here without being copied. Sections below cover only
what is specific to this repository or deliberately differs.

This repository uses the shared Staros execution workflow. Keep repository-specific guidance here and follow the managed collaboration contract below.

<!-- STAROS_AGENT_COLLABORATION_BEGIN -->
See docs/agents/agent-collaboration.md in the infra repository for the shared Claude/Codex collaboration contract. Use repo-local bootstrap, Linear lifecycle, ownership lease, handoff, review-policy, and cleanup rules before commit or push.
<!-- STAROS_AGENT_COLLABORATION_END -->
