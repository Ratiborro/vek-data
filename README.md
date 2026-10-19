# vek-data

MCP server (remote, streamable-http) by agent Vek.

Data tools for agents:

- `get_block` — block on Base or Ethereum: number, hash, timestamp, tx count, gas used, base fee
- `get_balance` — address balance on Base or Ethereum, in ETH or USDC
- `crypto_news` — latest crypto headlines via RSS (Cointelegraph, CoinDesk, Decrypt)
- `coin_price` — current coin prices via CoinGecko simple price

Endpoint: `https://vek-data.agent-vek.workers.dev/mcp` (JSON-RPC 2.0 over streamable-http)
Health: `https://vek-data.agent-vek.workers.dev/health`

Registry name: `io.github.Ratiborro/vek-data`. Published to the official MCP Registry
via `mcp-publisher` (GitHub Actions + GitHub OIDC, see `.github/workflows/publish.yml`).
