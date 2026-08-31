# davidondrej-skills

David Ondrej's official Agent Skills.

This repository contains reusable skills for AI coding agents, research agents,
and workflow agents. Each skill packages a focused workflow into instructions
that an agent can load when the task calls for it.

Use these skills as practical building blocks for agentic work: improving
codebases, preparing content, researching ideas, reviewing presentations,
working with transcripts, and other repeatable workflows from David's stack.

Skills are grouped into category folders under `skills/`. Each skill lives in
its own folder and starts with a `SKILL.md` file that explains when and how to
use it.

## Provenance and public-safety boundary

The source URL for this checkout is
`https://github.com/bhanunuthakki/skills_davidondrej.git`, but ownership and a
release manifest were not independently verified. Treat the checked-in skills
as an unverified snapshot until that provenance is confirmed. Do not copy private prompts, credentials,
local paths, or source documents into this repository. A future sync should
record the upstream URL, revision, date, and sanitization result in a reviewed
metadata file, then run a secret/path scan before opening a change. If those
facts cannot be established, archive this mirror rather than presenting it as
official or current.

- `skills/agent-orchestration/` — Running, scheduling, delegating to, and coordinating AI coding agents, including agent-to-agent workflows, agent loops, and agent benchmarks.
- `skills/skill-authoring/` — Creating, improving, distributing, and publishing Agent Skills and agent context files.
- `skills/research-and-web/` — Finding and pulling information from the web, research APIs, browsers, and YouTube.
- `skills/thinking-and-docs/` — Structured thinking, interviewing, teaching, and turning ideas into clear documentation.
- `skills/ops-and-setup/` — Machine, server, security, and tool setup, configuration, and operations.
