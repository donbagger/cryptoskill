---
name: dexpaprika-mcp
description: "Official DexPaprika MCP server providing DEX data on 33M+ tokens and 36M+ pools across 36 blockchain networks."
version: 1.1.0
metadata:
  openclaw:
    tags: [dexpaprika, dex, tokens, market-data, official]
    official: true
    source: "https://github.com/coinpaprika/dexpaprika-mcp"
---

# DexPaprika MCP Server

Official MCP server from CoinPaprika.

Official DexPaprika MCP server providing DEX data on 33M+ tokens and 36M+ pools across 36 blockchain networks. Access decentralized exchange analytics, token metrics, and market data through a structured MCP interface. The self-host npm build registers 16 read tools; the hosted server registers 17 (the same 16 plus submitFeedback). Free tier: 200,000 requests/month keyless per IP or 500,000 with a free key, both at 30 requests/minute, with data delayed up to 15 seconds. Pro is $99/month for 5,000,000 requests at 300/minute with real-time data.

## Installation

```bash
# npm (local)
npx dexpaprika-mcp@latest

# Claude Code
claude mcp add dexpaprika -- npx dexpaprika-mcp@latest

# Hosted (zero setup)
claude mcp add dexpaprika --transport http https://mcp.dexpaprika.com/streamable-http
```

## Links

- **GitHub**: https://github.com/coinpaprika/dexpaprika-mcp
- **Hosted MCP**: https://mcp.dexpaprika.com
- **API Docs**: https://docs.dexpaprika.com
- **npm**: https://www.npmjs.com/package/dexpaprika-mcp
