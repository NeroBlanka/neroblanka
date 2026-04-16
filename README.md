# NeroBlanka — Claude Code Skills

A collection of Claude Code skills and personal commands.

## Skills

| Skill | Description |
|-------|-------------|
| `autoplan` | Auto-review pipeline |
| `benchmark` | Performance regression detection |
| `browse` | Fast headless browser for QA testing |
| `canary` | Post-deploy canary monitoring |
| `careful` | Safety guardrails for destructive commands |
| `checkpoint` | Save and resume working state |
| `code-reviewer` | Comprehensive code review |
| `codex` | OpenAI Codex CLI wrapper |
| `connect-chrome` | Connect Chrome to Claude |
| `content-creator` | SEO-optimized marketing content |
| `cso` | Chief Security Officer audit mode |
| `design-consultation` | Design landscape research and proposals |
| `design-html` | Production-quality HTML/CSS generation |
| `design-review` | Visual QA and consistency checks |
| `design-shotgun` | Generate multiple AI design variants |
| `devex-review` | Live developer experience audit |
| `document-release` | Post-ship documentation update |
| `freeze` | Restrict file edits to a specific directory |
| `gstack` | Headless browser QA and dogfooding |
| `gstack-upgrade` | Upgrade gstack to the latest version |
| `guard` | Full safety mode |
| `health` | Code quality dashboard |
| `investigate` | Systematic debugging with root cause analysis |
| `land-and-deploy` | Merge PR, wait for CI, verify production |
| `learn` | Manage project learnings |
| `office-hours` | YC Office Hours mode |
| `open-gstack-browser` | Launch GStack Browser |
| `pair-agent` | Pair a remote AI agent with your browser |
| `plan-ceo-review` | CEO/founder-mode plan review |
| `plan-design-review` | Designer's eye plan review |
| `plan-devex-review` | Developer experience plan review |
| `plan-eng-review` | Eng manager-mode plan review |
| `qa` | Systematically QA test and fix bugs |
| `qa-only` | Report-only QA testing |
| `retro` | Weekly engineering retrospective |
| `review` | Pre-landing PR review |
| `setup-browser-cookies` | Import cookies into headless browser |
| `setup-deploy` | Configure deployment settings |
| `ship` | Full ship workflow |
| `unfreeze` | Clear the freeze boundary |

## Personal Commands

| Command | Description |
|---------|-------------|
| `/prime` | Load vault context at the start of a session |
| `/save` | Save current session state |
| `/ingest` | Ingest raw content into the wiki |
| `/lint` | Lint and health-check the vault |
| `/query` | Deep search in the wiki |

## Installation

Copy the skills into your `~/.claude/skills/` directory and the commands into `~/.claude/commands/`.

```bash
cp -r skills/* ~/.claude/skills/
cp commands/*.md ~/.claude/commands/
```
