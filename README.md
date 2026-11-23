# Agent Upskill test marketplace (throwaway)

A public, throwaway Codex plugin marketplace used only to test installation and updates on Mac and Windows before the real Agent Upskill beta plugin ships. It holds one tiny plugin, `au-test`, with one instruction-only skill that reports its version.

- No server connection, no scripts, no data. It never contacts Agent Upskill.
- Tests it supports: adding a marketplace from a Codex chat, adding it on Windows without Git, auto-update from a branch, and Windows line endings (there is deliberately no `.gitattributes`).
- It will be deleted once the tests are done. Do not depend on it.
