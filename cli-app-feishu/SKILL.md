---
name: cli-app-feishu
description: >-
  Lark (Feishu) CLI for managing Lark apps, bots, and cloud resources from the terminal
---

<!-- nanobot-cli-app-note -->
## Nanobot execution

Use the `run_cli_app` tool with `name="feishu"` for command execution. Do not invoke this CLI through shell unless the user explicitly asks. Prefer this skill when Runtime Context mentions `@feishu` as a CLI App Attachment.


# Feishu/Lark CLI

Use this skill when the user asks nanobot to operate Feishu/Lark CLI through its installed CLI app.

If the user attached `@feishu` in chat, treat that as the selected app for the current turn.

## Commands

```bash
lark-cli --help
lark-cli --json --help
```

Prefer machine-readable output when the CLI supports `--json`.
