# Olá, eu sou o Eric 👋

Desenvolvedor backend. Trabalho com **PHP/Laravel** em produção e estudo arquitetura de sistemas distribuídos com **TypeScript** e **Go**.

## 🚀 Projeto em destaque: plataforma de trading em microserviços

[**software-architecture-practice**](https://github.com/erichenriquesm/software-architecture-practice): uma exchange simplificada, especificada antes de ser implementada (spec-driven), com cinco serviços independentes, cada um no seu repositório:

| Serviço | O que faz |
|---|---|
| [account](https://github.com/erichenriquesm/software-architecture-practice-account) | Cadastro e consulta da conta, com saldos projetados da carteira |
| [wallet](https://github.com/erichenriquesm/software-architecture-practice-wallet) | Depósito, saque, reserva de saldo e liquidação, com ledger de auditoria |
| [order](https://github.com/erichenriquesm/software-architecture-practice-order) | Ordens limitadas, máquina de estados e dono das sagas de ordem |
| [matching](https://github.com/erichenriquesm/software-architecture-practice-matching) | Motor do livro de ofertas: prioridade preço-tempo e prevenção de self-trade |
| [market-data](https://github.com/erichenriquesm/software-architecture-practice-market-data) | Profundidade do livro, negociações e estatísticas de 24 h por projeções |

**Conceitos aplicados:** DDD, Clean Architecture (Ports & Adapters), CQRS, sagas coreografadas, outbox/inbox, retry com backoff e DLQ, gRPC entre serviços, rate limiting e testes de integração com infraestrutura efêmera.

## 🛠️ Stack

- **Linguagens:** PHP, TypeScript/Node.js, Go, Python
- **Frameworks:** Laravel, Fastify, Gin
- **Dados e mensageria:** PostgreSQL, Redis, RabbitMQ
- **Infra e testes:** Docker, Docker Compose, Vitest, Pest

## 📌 Outros projetos

- [laravel-layer](https://github.com/erichenriquesm/laravel-layer): base Laravel com arquitetura hexagonal, domain events via RabbitMQ e Pest
- [financial-track-back](https://github.com/erichenriquesm/financial-track-back): API de controle de despesas em Go (Gin, GORM, JWT)
- [mcp-proof-of-concept](https://github.com/erichenriquesm/mcp-proof-of-concept): servidor MCP (Model Context Protocol) em TypeScript

## 📚 Estudando agora

Padrões de arquitetura distribuída, mensageria e integração de IA em aplicações (MCP).
