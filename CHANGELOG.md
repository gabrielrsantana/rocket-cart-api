# 📜 Changelog

Todas as mudanças importantes neste projeto serão documentadas aqui.

O formato deste changelog é baseado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/).

---

## [0.1.0] - 2025-06-11

### 🚀 Added
- Initial project structure **rocket-cart-api** utilizando:
    - Java 17
    - Spring Boot
    - Maven
    - PostgreSQL
- First Endpoints :
    - `/parts` para listagem de peças.
    - `/cart` para gerenciar itens do carrinho.
    - `/parts/category/{categoryName}` para listar peças por categoria.

### 🔧 Infraestrutura
- Creation of the folders `docker/` on project root.
- Added `docker-compose.yml` to provision the PostgreSQL data source

---

## [Unreleased]

### 🔥 Planejado
- Creation of endpointt `/cart/checkout` (opcional).
- unit testing and integration testing.
- Criação do `Dockerfile` para containerizar a aplicação Spring Boot.

---

