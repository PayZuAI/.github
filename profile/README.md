<div align="center">

# PayZu AI

**Ferramental aberto de IA e desenvolvimento da [PayZu](https://payzu.com.br)** — infraestrutura de pagamentos Pix para quem constrói produto.

[Site](https://payzu.com.br) · [Documentação](https://docs.payzu.com.br) · [Abrir conta](https://abrirconta.payzu.com.br)

</div>

---

## Projetos

| Projeto | O que faz |
|---|---|
| [payzu-mcp](https://github.com/PayZuAI/payzu-mcp) | Servidores MCP das APIs PayZu (Pix Processamento e Conta Digital). Conecte sua conta ao Claude, Cursor, Windsurf ou qualquer agente de IA e opere por conversa: crie cobranças, consulte saldo, acompanhe transações. |

## Sua conta PayZu conversando com IA

Com o [MCP](https://modelcontextprotocol.io) (Model Context Protocol), seu assistente de IA passa a ter acesso direto à sua conta — com o seu token, sob o seu controle:

```json
{
  "mcpServers": {
    "payzu-pix": {
      "command": "npx",
      "args": ["-y", "payzu-mcp-pix"],
      "env": { "PAYZU_TOKEN": "seu-token" }
    }
  }
}
```

> Token disponível no painel em [abrirconta.payzu.com.br](https://abrirconta.payzu.com.br). Guia completo na [documentação](https://docs.payzu.com.br/docs/pix-processamento/mcp).

## Contato

Dúvidas e parcerias: **developer@payzu.com.br**
