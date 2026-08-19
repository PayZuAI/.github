<div align="center">

# PayZu AI

**Ferramental aberto de IA e desenvolvimento da [PayZu](https://payzu.com.br).** Infraestrutura de pagamentos Pix para quem constrói produto.

[Conecte sua IA](https://ia.payzu.com.br) · [Site](https://payzu.com.br) · [Documentação](https://docs.payzu.com.br)

</div>

---

## Projetos

| Projeto | O que faz |
|---|---|
| [payzu-mcp](https://github.com/PayZuAI/payzu-mcp) | Servidor MCP da API Pix Processamento. Conecte sua conta ao Claude, Cursor, Windsurf ou qualquer agente de IA e opere por conversa: crie cobranças, consulte saldo, acompanhe transações. |
| [payzu-sdks](https://github.com/PayZuAI/payzu-sdks) | SDKs oficiais da PayZu Pix API. [npm](https://www.npmjs.com/package/payzu-pix), [PyPI](https://pypi.org/project/payzu-pix/), Go e PHP, gerados do OpenAPI. |

## Sua conta PayZu conversando com IA

Com o [MCP](https://modelcontextprotocol.io) (Model Context Protocol), seu assistente de IA passa a ter acesso direto à sua conta — com o seu token, sob o seu controle.

**No claude.ai ou Claude Desktop** (mais fácil): Configurações → Conectores → *Adicionar conector personalizado* → cole a URL abaixo. Uma página da PayZu abre pedindo autorização — e pronto.

```
https://mcp.payzu.processamento.com/mcp
```

**No Cursor, VS Code ou Windsurf**: um clique —

[![Install in Cursor](https://img.shields.io/badge/Cursor-Instalar-000000?logo=cursor)](https://cursor.com/en/install-mcp?name=payzu-pix&config=eyJ1cmwiOiJodHRwczovL21jcC5wYXl6dS5wcm9jZXNzYW1lbnRvLmNvbS9tY3AifQ%3D%3D)
[![Install in VS Code](https://img.shields.io/badge/VS_Code-Instalar-0098FF?logo=githubcopilot)](https://insiders.vscode.dev/redirect/mcp/install?name=payzu-pix&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.payzu.processamento.com%2Fmcp%22%7D)

**Instalador pro Claude Desktop** (offline/local): baixe o [payzu-mcp-pix.mcpb](https://github.com/PayZuAI/payzu-mcp/releases/latest) e abra o arquivo — o Claude pede só o token.

> Token disponível no dashboard: [Processamento → Credenciais](https://web.payzu.processamento.com/credentials) ou [Hub → Tokens](https://hub.payzu.com.br/settings/tokens). Guia completo na [documentação](https://docs.payzu.com.br/docs/pix-processamento/mcp).

## Contato

Dúvidas e parcerias: **developer@payzu.com.br**
