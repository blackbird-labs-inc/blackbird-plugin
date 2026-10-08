# Blackbird Concierge

Get access to reservations & recommendations at top restaurants.

This repository is a Cursor Marketplace with one plugin, **Blackbird Concierge**. Blackbird's MCP gets you access to book, reserve, and explore reservations via OpenTable, Resy, and SevenRooms. It can help you find the right reservation based on your taste profile generated from your past restaurant check-ins and payments.

The plugin lives in `plugins/blackbird-concierge` and connects to `https://concierge.api.blackbird.xyz/mcp`.

## Links

- Documentation: https://docs.flynet.org/
- Privacy policy: https://www.blackbird.xyz/privacy
- Support: support@blackbird.xyz

## Validate

```bash
node scripts/validate-template.mjs
```

To add another plugin later, see `docs/add-a-plugin.md`.
