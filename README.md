# 🎨 DesignForge MCP

**Autonomous Design Systems Engineering, Design Tokens, Theming & WCAG Accessibility Engine MCP**

[![MCP](https://img.shields.io/badge/MCP-Server-blueviolet)](https://modelcontextprotocol.io)
[![Smithery](https://img.shields.io/badge/Smithery-DesignForge-green)](https://smithery.ai)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

96% of the top 1,000,000 websites fail WCAG accessibility checks. Teams rebuild buttons, rewire dark mode, and fight inconsistent spacing on every project. DesignForge turns your AI agent (Cursor, Claude Code, any MCP client) into a **senior design systems engineer** that architects tokens, theming, components, accessibility, and governance — end to end.

## 🚀 Live Endpoint

```
https://designforge-api.agentweb-hub.workers.dev/mcp
```

Streamable HTTP MCP — works with Cursor, Claude Code, Claude Desktop, Windsurf, and any MCP client.

## 🛠️ Tools (5)

| Tool | What it does |
|------|-------------|
| `autonomous_design_system_architect` | Full design system blueprint: 3-tier token architecture, styling stack decision (Tailwind v4 / CSS vars / vanilla-extract), component strategy (shadcn copy-in vs headless vs library), multi-brand theming plan, governance model by team size, incremental adoption roadmap |
| `generate_design_tokens` | Production-ready design tokens in Tailwind v4 `@theme`, CSS custom properties, or W3C DTCG tokens JSON — OKLCH color scales, semantic tier, dark-mode remap, no-flash head script |
| `build_component_architecture` | Headless component architecture: CVA variant patterns, compound components, Radix / React Aria / Base UI integration, Storybook + interaction testing strategy |
| `implement_accessible_ui` | WCAG 2.2 AA remediation engine: top failure fixes with reference code (focus management, live regions, form wiring, reduced motion), token-level contrast CI, ADA / EAA / VPAT / Section 508 guidance |
| `prepare_design_system_release` | Ship your design system: semver + changesets vs copy-in registry, docs strategy, codemods, lint-ratchet adoption, contribution model, go-live checklist |

## ⚡ Quick Start (Cursor / Claude Code)

```json
{
  "mcpServers": {
    "designforge": {
      "url": "https://designforge-api.agentweb-hub.workers.dev/mcp"
    }
  }
}
```

## 💰 Pricing

- **Free tier**: 10 requests/day — no signup
- **Pro ($7.99)**: unlimited DesignForge access — [Get Pro key](https://amygraphics.gumroad.com/l/mcp-pro)
- **All-Access ($14.99 lifetime)**: unlimited access to all 43+ MCP servers in the suite
- **Crypto**: pay with Solana USDC — see `/verify-solana` endpoint

## 🌐 More Servers

Browse all 43 autonomous MCP servers: [MCP Hub](https://mcp-hub.agentweb-hub.workers.dev)

## 📄 License

MIT © AmyGraphics
