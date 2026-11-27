# Logsblox plugins

This repository is the Logsblox Cursor plugin collection. It holds both the Cursor plugin and the Claude Code plugin.

## logsblox

The [`logsblox`](logsblox/) plugin gives agents access to Logsblox projects and immutable application logs.

Install **Logsblox** from the Cursor marketplace (**Browse MCPs**). It connects to the existing MCP server at `https://mcp.logsblox.com`.

In Claude Code, add this marketplace and install the plugin:

```bash
claude plugin marketplace add logsblox/lbx-plugins
claude plugin install logsblox@logsblox
```

Details are in [logsblox/README.md](logsblox/README.md).
