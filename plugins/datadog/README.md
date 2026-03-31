Vendored from [datadog-labs/cursor-plugin](https://github.com/datadog-labs/cursor-plugin) (Apache-2.0). See `LICENSE` and `NOTICE` in this folder.

> **This plugin is currently in Preview.**

# Datadog Cursor Plugin

Query Datadog directly from Cursor using natural language. Ask about logs, metrics, traces, dashboards, monitors, and more.

## What you need

- A [Datadog](https://www.datadoghq.com/) account
- [Cursor](https://cursor.com/) IDE (v2.6.0+)

## Getting started

> If you already have the Datadog MCP server registered separately (e.g. in `.cursor/mcp.json`), disable or remove it first to avoid conflicts.

1. Open Cursor Settings (gear icon or **Cursor Settings: Tools & MCP** in the Command Palette).
2. Go to the **Plugins** section.
3. Install the **datadog** plugin from this marketplace.

Before using the MCP server installed by the plugin, select your Datadog domain and complete OAuth sign-in.

## Can't connect?

Run the `/datadog-mcp-setup` command in Cursor or follow `skills/datadog-mcp-setup/SKILL.md`.

## Support

- [Datadog MCP Server Documentation](https://docs.datadoghq.com/bits_ai/mcp_server/)
