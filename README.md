MCPmarket plugin for Claude Code.

## Install

Install via Claude's plugin marketplace:

```
claude plugin marketplace add knoxgraeme/mcpmarket-plugin
```

Or download a pre-configured ZIP from https://app.mcpmarket.com.

## Layout

- `.claude-plugin/plugin.json` — plugin manifest
- `.mcp.json` — MCP server config (toolkit URL + API token)
- `hooks/hooks.json` — `SessionStart` hook
- `hook-shim.sh` — exports `MCPMARKET_*` env vars then runs `shared/sync.sh`

The shared sync logic lives in `shared/sync.sh`.
Updates for main to the layout section to provide more clarity on file structure and bugging machanism.

feature update 2
feature update 3
