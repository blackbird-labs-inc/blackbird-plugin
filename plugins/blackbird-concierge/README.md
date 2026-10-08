# Blackbird Concierge

Get access to reservations & recommendations at top restaurants.

Blackbird's MCP gets you access to book, reserve, and explore reservations via OpenTable, Resy, and SevenRooms. It can help you find the right reservation based on your taste profile generated from your past restaurant check-ins and payments.

## What it does

- Book, reserve, and explore reservations through OpenTable, Resy, and SevenRooms.
- Recommend restaurants that match the member's taste profile from past check-ins and payments.

## MCP server

Remote HTTP MCP:

```json
{
  "mcpServers": {
    "blackbird-concierge": {
      "url": "https://concierge.api.blackbird.xyz/mcp"
    }
  }
}
```

Endpoint: `https://concierge.api.blackbird.xyz/mcp`

## Install

Install **Blackbird Concierge** from this Cursor Marketplace. Cursor loads `mcp.json` and the booking skill automatically.

Before booking or recommending, the agent should read `skills/blackbird-concierge/SKILL.md`: use Concierge tools for search, availability, and booking; prefer the member's taste profile; confirm party size, date/time, and restaurant; and never invent availability.

## Links

- Documentation: https://docs.flynet.org/
- Privacy policy: https://www.blackbird.xyz/privacy
- Support: support@blackbird.xyz

## Authentication

TODO: Auth for the Concierge MCP was not specified. `mcp.json` points at the remote URL with no token or headers. If the endpoint requires a token or header, add it there before use. Do not commit secrets.
