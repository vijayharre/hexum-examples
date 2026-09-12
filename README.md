# hexum-examples

Copy-paste `architecture.hexum` files and MCP snippets for [hexum.dev](https://hexum.dev).

Hexum is the layer next to Cursor, Claude Code, Codex, Antigravity, and Grok. One key. This repo is not the product binary. It is the public contract: a rules file, a JSON snippet, a license you can copy.

Not Hex.tech, Hexium, or the face-score app.

## What to copy

| Path | Job |
|---|---|
| `mcp.json` | Cursor / VS Code MCP config. Replace the key. |
| `architecture.hexum` | Minimal layers + one forbid. |
| `templates/nextjs.hexum` | App / components / services / data. |
| `templates/rails.hexum` | Controllers / services / models. |
| `templates/python-services.hexum` | API / domain / adapters. |

## MCP (same key on every agent)

```json
{
  "mcpServers": {
    "hexum": {
      "serverUrl": "https://hexum.dev/mcp",
      "headers": { "Authorization": "Bearer hexum_live_…" }
    }
  }
}
```

Install pages: [Cursor](https://hexum.dev/cursor) · [Claude Code](https://hexum.dev/claude-code) · [Codex](https://hexum.dev/codex)

`hexum_check` reads `architecture.hexum`. It does not call a model.

## Proof

Published card: combined 220,393 → 27,352 tokens (−87.6%), 24/24 pass. Estimator `ceil(utf8_bytes/4)`, not a provider invoice. [hexum.dev/benchmarks](https://hexum.dev/benchmarks)

## License

MIT. The examples are yours to paste. Hexum the service is not.
