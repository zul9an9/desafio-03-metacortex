# Desafio 03 — cenário Metacortex

Repositório próprio da entrega do Desafio 03 (quatro tickets). Todo o conteúdo está em
[`desafio-03/`](desafio-03/), que começa pelo [`README.md`](desafio-03/README.md) com o detalhe de
cada ticket, o agente e os modelos usados.

## Tickets

| # | Ticket | Tipo | Agente / ferramenta | Modelo(s) |
|---|---|---|---|---|
| 01 | [Padrão de manifests](desafio-03/ticket-01-padrao-de-manifests/) | Skill | Claude no claude.ai, com execução de código, seguindo o guia `skill-creator` | Claude Opus 5 |
| 02 | [Triagem no cluster](desafio-03/ticket-02-triagem-no-cluster/) | Skill | claude.ai para escrever a skill; Claude Code em sessões limpas para medir | Claude Opus 5 (claude.ai) · Claude Sonnet 5 (Claude Code) |
| 03 | [Inventário de VM](desafio-03/ticket-03-inventario-de-vm/) | Projeto (OpenSpec) | claude.ai para brainstorm e revisões; Claude Code com `/opsx:*` | Claude Opus 4.8 (brainstorm e spec) · Claude Sonnet 5.5 (implementação) |
| 04 | [Dashboard do cluster](desafio-03/ticket-04-dashboard-do-cluster/) | Projeto (OpenSpec) | Claude Code com `/opsx:*`, usando as skills dos tickets 01 e 02 | Claude Opus 4.8 (brainstorm e spec) · Claude Sonnet 5.5 (implementação) |
