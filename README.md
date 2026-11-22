# Archify · SISJOGOS

Arquitetura do **SISJOGOS** (Jogos Bom de Ginga 2026) no padrão **C4 Model**, em um único `index.html` interativo feito com HTML, CSS e JavaScript puros, sem frameworks.

- **Nível 1 · Contexto**: atores, o SISJOGOS e os sistemas externos.
- **Nível 2 · Containers**: SPA React, Nginx, API Spring Boot, MySQL, RabbitMQ, observabilidade e backups.
- **Nível 3 · Componentes**: segurança, controllers, services, motor de avaliação, chaveamento, eventos, SSE e mensageria.
- **Nível 4 · Código e Dados**: as 21 tabelas principais (entidades JPA + Flyway) com campos, chaves e cardinalidades, coloridas por área do domínio.
- **Fluxo crítico**: diagrama de sequência animado do `POST /api/avaliacoes/lancar` até o telão, com os dois cenários (ainda falta árbitro e último lançamento).
- **Integridade, decisões (ADRs) e stack** por camada.

Clique em um card para ver responsabilidades, stack, endpoints, campos e regras de negócio; use o ícone de zoom (ou duplo clique) para descer ao próximo nível. Atalhos: `Ctrl K` ou `/` busca, `1` a `4` níveis, `+` `-` `0` zoom, `F` tela cheia, `Esc` fecha, `←` `→` e espaço controlam o fluxo crítico.

Fonte: board do C4 Model no Miro e o código da branch `develop` do SISJOGOS.

Publicado com GitHub Pages a partir da branch `main` (pasta raiz).
