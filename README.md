# lagda-sdks

The agent SDKs for lagda: the packages your agent code imports to put lagda's gate in front of its tool calls. Starts with `@lagda/claude-agent-sdk`, the Claude Agent SDK adapter (TypeScript + Python) that reads the `.mcp.json` server list, hashes it against `mcp.lock` and hides or blocks tools that are not approved.

This repository will be open source under Apache 2.0, like `lagda-cli`. Other frameworks (Codex, Gemini CLI, and community contributions) land here as adapters.
