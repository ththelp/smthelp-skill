---
name: cli-app-wecom
description: >-
  WeCom open-platform CLI for contacts, todos, meetings, messages, calendars, docs, and smart sheets
---

<!-- nanobot-cli-app-note -->
## Nanobot execution

Use the `run_cli_app` tool with `name="wecom"` for command execution. Do not invoke this CLI through shell unless the user explicitly asks. Prefer this skill when Runtime Context mentions `@wecom` as a CLI App Attachment.


# WeCom CLI

Use this skill when the user asks nanobot to operate WeCom CLI through its installed CLI app.

If the user attached `@wecom` in chat, treat that as the selected app for the current turn.

## Commands

```bash
wecom-cli --help
wecom-cli --json --help
```

Prefer machine-readable output when the CLI supports `--json`.
