# Instalação detalhada

Laudos Veiculares DEKRA: LCD (Classificação de Danos) é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_laudos_veiculares_dekra_lcd`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_laudos_veiculares_dekra_lcd` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_laudos_veiculares_dekra_lcd` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_laudos_veiculares_dekra_lcd` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.laudos_veiculares_dekra_lcd` (ou `servers.laudos_veiculares_dekra_lcd` no VS Code) do config do cliente e reinicie.
