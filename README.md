# TarsWazuh

MCP integration for Wazuh (open source security platform).

## Tools

- `wazuh_agents` — List active Wazuh agents
- `wazuh_alerts` — Query recent security alerts

## Quick Start

```bash
go build -o tarswazuh
TARS_MCP_ENDPOINT=https://api.example.com TARS_MCP_API_KEY=xxx ./tarswazuh
```

## Environment Variables

- `TARS_MCP_ENDPOINT` — upstream API endpoint
- `TARS_MCP_API_KEY` — upstream API key
- `TARS_MCP_MODE` — `stdio` (default) or `http`

## License

MIT
