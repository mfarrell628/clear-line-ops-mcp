# Clear Line Ops MCP Server

A hosted remote MCP server with 150+ tools for engineering, architecture, research and automation. Nothing to install: connect your MCP client to the URL below. Built by Mark Farrell.

**Endpoint:** `https://mcp.clear-line-operations.com/mcp` (streamable HTTP, Bearer API key)
**Site and free trial:** https://mcp.clear-line-operations.com (25 free credits, no card)

## What it does

- **Engineering and CAD:** describe a project in plain language and get a 3D model, DXF cut layout, cut list, bill of materials and build steps (`cad_build`); mechanical parts, gears, gearboxes, beam and fastener calculators; scan or mesh (STL/OBJ/PLY) to dimensioned CAD drawings (`cad_reverse`). Web workbench at `/engineering`.
- **Architecture:** a one-line brief becomes a laid-out floor plan, 3D walk-through studio, IFC/DXF/STL export and a bill of materials priced from live market data (`arch_design`, `arch_review`). Free sample at `/architects`.
- **Web and research:** search, scraping, extraction, crawling, DNS/TLS/security checks, feeds, sitemaps.
- **Website builder:** generate and host sites and front ends instantly.
- **Media:** FFmpeg audio and video conversion, captions, transcription.
- **Crime and cyber research, crypto and markets, ads and marketing, game and music tools.**

Weapons, ammunition, explosives and military platform design requests are refused.

## Connect

```json
{
  "mcpServers": {
    "clear-line-ops": {
      "url": "https://mcp.clear-line-operations.com/mcp",
      "headers": { "Authorization": "Bearer YOUR_API_KEY" }
    }
  }
}
```

Get a key from the free trial on the site.

## Pricing

Free trial (25 credits), Day pass $9, Week pass $29, Monthly $79, credit packs from $5. Most tool calls cost 1 credit; failed calls are refunded.

## Links

- Tool browser: https://mcp.clear-line-operations.com/app
- Engineering workbench: https://mcp.clear-line-operations.com/engineering
- Architects: https://mcp.clear-line-operations.com/architects
- Terms: https://mcp.clear-line-operations.com/terms
- Privacy: https://mcp.clear-line-operations.com/privacy
