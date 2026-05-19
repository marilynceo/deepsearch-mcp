# deepsearch-mcp

Multi-engine web search (Brave, Google, Bing) with page fetching, structured extraction, news, images, and advanced filters u2014 directly from your AI agent.

## Quick Start

```bash
git clone https://github.com/marilynceo/deepsearch-mcp.git
cd deepsearch-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://deepsearch.zhc-mcp.org

## Tools

| Tool | Description |
|------|-------------|
| `web_search` | Search query |
| `search_images` | Image search query |
| `search_news` | News search query |
| `fetch_page_content` | URL to fetch |
| `extract_structured_data` | URL to fetch and extract from |
| `search_domain` | Search query |
| `related_searches` | Query to find related searches for |

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/deepsearch-mcp

# Or connect directly via MCP client
# Endpoint: https://deepsearch.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
