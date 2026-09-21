# Lots of Sounds MCP

Remote [Model Context Protocol](https://modelcontextprotocol.io) server for [Lots of Sounds](https://www.lotsofsounds.com) — a CC0 royalty-free sound effects API for developers and AI agents.

## Endpoint

- **URL:** `https://api.lotsofsounds.com/mcp`
- **Transport:** Streamable HTTP
- **Auth:** optional `x-api-key` header (API keys from https://www.lotsofsounds.com/dashboard/api-keys). `browse_samples` works without a key.

## Docs

- MCP docs: https://www.lotsofsounds.com/docs/mcp
- API docs: https://www.lotsofsounds.com/docs
- Privacy: https://www.lotsofsounds.com/privacy
- Terms: https://www.lotsofsounds.com/terms

## Cursor example

```json
{
  "mcpServers": {
    "lotsofsounds": {
      "url": "https://api.lotsofsounds.com/mcp",
      "headers": { "x-api-key": "los_your_key" }
    }
  }
}
```

Shipping product: https://github.com/lotsofsounds/lots-of-sounds  
Public API wrapper: https://github.com/lotsofsounds/free-sound-effects-api
