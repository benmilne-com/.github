# benmilne.com

Open source code and agent discovery resources for [benmilne.com](https://benmilne.com) — the personal site of [Ben Milne](https://benmilne.com/about), founder of [Brale](https://www.brale.xyz/).

## What's here

### [x402-payment-path](https://github.com/benmilne-com/x402-payment-path)

A library for gating any action behind [x402](https://www.x402.org/) stablecoin payments. Agent-first, server-side, no client UI. One function call to accept SBC or USDC on Base, Solana, and Radius. Powers the `/contact/send` endpoint on benmilne.com — [read the write-up](https://benmilne.com/talking-to-agents).

### [agents](https://github.com/benmilne-com/agents)

Agent discovery configuration for benmilne.com. Includes install configs for VS Code, Cursor, Claude, and Windsurf, plus the MCP server card used by the [MCP Registry](https://registry.modelcontextprotocol.io/).

## The site

benmilne.com is a Cloudflare Workers application — edge-first, protocol-native, no external frameworks. Content is served as HTML, JSON, or Markdown from the same URL via content negotiation. 73 posts in 14 languages. Public API, RSS feeds, OpenAPI spec, MCP tools, and structured data throughout.

- **API**: [benmilne.com/api](https://benmilne.com/api) — public, no auth required
- **OpenAPI**: [benmilne.com/openapi.json](https://benmilne.com/openapi.json)
- **MCP**: [benmilne.com/developers](https://benmilne.com/developers)
- **RSS**: [benmilne.com/rss](https://benmilne.com/rss)
- **Agent discovery**: [benmilne.com/agents.md](https://benmilne.com/agents.md)

## License

Code in these repositories is MIT licensed.
