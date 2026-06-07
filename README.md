# 🇧🇷 Conhece-Brasil

Jogo de cartas educativo sobre as cidades e estados do Brasil. Funciona no celular, **online ou offline**, em um único arquivo (`index.html`).

🎮 **Jogar agora:** _(coloque aqui o link do seu GitHub Pages, ex.: https://SEU-USUARIO.github.io/conhece-brasil/)_

## Como jogar

De **1 a 8 jogadores** (dá pra jogar sozinho para testar seus conhecimentos). O jogo começa no nível 1 e sobe sozinho a cada 5 acertos, até o nível 3. São três tipos de carta:

- ⚡ **Relâmpago** — pergunta rápida com 4 opções e 15 segundos, sobre estados e cidades do Brasil.
- 🔍 **Detetive** — descubra em que estado/região fica uma cidade, ou adivinhe a nota de qualidade de vida (IPS) pelas pistas. A cidade aparece no mapa.
- 🔥 **Desafio** — compare duas cidades por um indicador. Acerte **e** explique o porquê para ganhar ponto dobrado (o organizador julga).

Todas as cartas mostram um mapa: **Leaflet + OpenStreetMap** quando há internet, e um mapa do Brasil em canvas quando offline.

## Dados

Todos os valores são **reais**, extraídos do IPS Brasil 2026 e do IBGE Localidades 2022, cobrindo os 5.570 municípios brasileiros. Nenhum valor é inventado — inclusive as alternativas erradas usam valores reais de outras cidades.

## Tecnologia

Arquivo único (`index.html`) com HTML, CSS, JS e dados embutidos. Sem dependências de build. A única biblioteca externa é o Leaflet (carregado via CDN apenas para o mapa online).

---

Idealizado por **Ernandes Sobreira**.
