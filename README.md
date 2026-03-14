# Binance MCP Server

MCP server for Binance. Agent-ready API for Binance.

Hosted at [binance.mcp.junct.dev/mcp](https://binance.mcp.junct.dev/mcp). Free to use. No auth. No API key required.

Part of [Junct](https://junct.dev) — the agent-readiness layer for the crypto stack.

## Quick Start

Add to your MCP client config (Claude Desktop, Cursor, Windsurf):

```json
{
  "mcpServers": {
    "binance": {
      "url": "https://binance.mcp.junct.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## About

This MCP server is **deterministically generated** from the Binance API specification. Every tool maps 1:1 to a real API endpoint — no hallucinated endpoints, no phantom tools.

- **Protocol:** Binance
- **Endpoint:** `https://binance.mcp.junct.dev/mcp`
- **Transport:** Streamable HTTP
- **Auth:** None required
- **Documentation:** [binance.mcp.junct.dev/llms.txt](https://binance.mcp.junct.dev/llms.txt)
- **Server card:** [binance.mcp.junct.dev/.well-known/mcp/server.json](https://binance.mcp.junct.dev/.well-known/mcp/server.json)

## Links

- [Junct Dashboard](https://junct.dev/servers/binance)
- [llms.txt](https://binance.mcp.junct.dev/llms.txt)
- [agents.md](https://binance.mcp.junct.dev/agents.md)
- [OpenAPI spec](https://binance.mcp.junct.dev/openapi.json)

## Keywords

Binance, MCP server, DeFi, AI agent, agent-ready API, crypto tools, Model Context Protocol, hosted MCP
