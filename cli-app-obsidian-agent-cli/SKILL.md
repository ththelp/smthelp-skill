---
name: cli-app-obsidian-agent-cli
description: >-
  Full-featured CLI for Obsidian — manage notes, canvases, Excalidraw diagrams, Kanban boards, periodic notes, git, tasks, and more. Includes an AI agent skill for persistent knowledge capture and project memory.
---

<!-- nanobot-cli-app-note -->
## Nanobot execution

Use the `run_cli_app` tool with `name="obsidian-agent-cli"` for command execution. Do not invoke this CLI through shell unless the user explicitly asks. Prefer this skill when Runtime Context mentions `@obsidian-agent-cli` as a CLI App Attachment.


# Obsidian CLI

Use this skill when the user asks nanobot to operate Obsidian CLI through its installed CLI app.

If the user attached `@obsidian-agent-cli` in chat, treat that as the selected app for the current turn.

## Commands

```bash
obsidian-agent --help
obsidian-agent --json --help
```

Prefer machine-readable output when the CLI supports `--json`.
