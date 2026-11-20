# prof2030-lab â€” Horizonte Distribuidora

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


LaboratÃ³rio de estudo do **Profissional 2030** (INEMA.CLUB, aberto e gratuito): uma empresa **fictÃ­cia** de 40 pessoas com **12 falhas de IA plantadas de propÃ³sito**, para treinar auditoria, consultoria e adoÃ§Ã£o segura de IA.

Site: https://inematds.github.io/prof2030-lab/ Â· Programa: https://inematds.github.io/profissional-2030/

> **Tudo aqui Ã© falso e proposital.** NÃ£o hÃ¡ servidor, banco de dados nem dado real. Chaves (`FAKE-EXEMPLO`), CPFs (invÃ¡lidos), telefones, pessoas e empresas sÃ£o inventados. Site estÃ¡tico: HTML, CSS e JS puro, sem build.

## Falhas plantadas

| CÃ³digo | PeÃ§a | Falha |
|---|---|---|
| F1 | `pecas/app-pedidos/` | chave de API (falsa) no JavaScript do navegador |
| F2 | `pecas/app-pedidos/` | tabela de pedidos sem RLS |
| F3 | `pecas/app-pedidos/admin.html` | rota de admin sem login |
| F4 | `pecas/app-pedidos/` | dependÃªncia velha com vulnerabilidade conhecida no `package.json` |
| F5 | `pecas/agente-whatsapp/` | desconto sem teto |
| F6 | `pecas/agente-whatsapp/` | aceita ordem escondida no texto do cliente (injeÃ§Ã£o de prompt) |
| F7 | `pecas/agente-whatsapp/` | sem registro nem aprovaÃ§Ã£o humana acima de R$ 5 mil |
| F8 | `pecas/planilha-clientes/` | planilha com CPF e telefone "qualquer pessoa com o link" |
| F9 | `pecas/mcp-email/` | MCP com enviar e apagar e-mail sem aprovaÃ§Ã£o |
| F10 | `pecas/resumo-atendimento/` | conversa de cliente para API estrangeira sem contrato nem base legal |
| F11 | `pecas/painel/` | painel sem linha de base |
| F12 | `inventario.html` | IA na sombra: 4 ferramentas que a TI nÃ£o conhece |

Respostas completas (onde, por quÃª, como corrigir, gravidade): `gabarito.html` (com aviso de spoiler).

## Como usar nos cursos

Os cursos Base, Consultor, Auditor, Mentor e Treinador mandam o aluno abrir uma peÃ§a, achar a falha pelo cÃ³digo F1â€“F12 e propor a correÃ§Ã£o. Os caminhos e cÃ³digos sÃ£o **fixos**: nÃ£o renomeie peÃ§as.

Pessoas fictÃ­cias: Carlos Mendes (dono), PatrÃ­cia Lima (gerente comercial), Rafael (TI terceirizada), Juliana (atendimento).

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>