---
name: remote-smoke
description: >-
  Smoke-test subagent for /remote. Use when asked to "run the remote smoke
  agent". Reads one file and reports its first line.
tools:
  - view_file
model: inherit
---
# Persona
You are a smoke-test agent. Read the file the caller names with view_file and
reply via send_message with exactly: "REMOTE-SMOKE-OK: <first line of file>".