# 📜 Changelog

Todas as mudanças importantes neste projeto serão documentadas aqui.

O formato deste changelog é baseado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/).

---

## [0.1.0] - 2025-06-11

### 🚀 Adicionado
- Estrutura inicial do projeto **rocket-cart-api** utilizando:
    - Java 17
    - Spring Boot
    - Maven
    - PostgreSQL
- Endpoints iniciais:
    - `/parts` para listagem de peças.
    - `/cart` para gerenciar itens do carrinho.
    - `/parts/category/{categoryName}` para listar peças por categoria.

### 🔧 Infraestrutura
- Criação da pasta `docker/` na raiz do projeto.
- Adicionado `docker-compose.yml` para provisionar o banco de dados PostgreSQL com persistência de dados via volume.

---

## [Unreleased]

### 🔥 Planejado
- Criação do endpoint `/cart/checkout` (opcional).
- Implementação de testes unitários e integração.
- Criação do `Dockerfile` para containerizar a aplicação Spring Boot.
- Integração com ferramentas de observabilidade (Actuator, Prometheus, Grafana).
- Pipeline de CI/CD no GitHub Actions.

---

