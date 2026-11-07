# QA da experiência

Os smoke tests da Tech Polis v0.6.11 passaram em previews independente e integrado ao mapa. Os resultados descrevem a versão avaliada; este showcase não distribui a suíte nem o pacote executável.

| Janela | Independente | Integrado |
| --- | --- | --- |
| 1440 × 1000 | Passou | Passou |
| 637 × 824 | Passou | Passou |
| 390 × 844 | Passou | Passou |
| 375 × 667 | Passou | Passou |

Foram verificados os quatro ambientes, a abertura de créditos por teclado, o retorno de foco no painel musical, a capa e o destino Spotify de Tech Polis II, a tiragem e o reembaralhamento do Tarot, e a ausência de rolagem horizontal indevida nos cenários testados. No modo integrado, a jornada começou no mapa, entrou em Tech Polis e voltou ao mapa.

## Conferência manual pela demo

1. No [mapa da Bomba Land](https://bomba-land.pages.dev/), entre em Tech Polis.
2. Abra Bomba Tech, retorne ao átrio e abra Leo’s House → Som da casa. Confira o título Tech Polis II e o destino Spotify.
3. No Jardim do Conhecimento, abra UNKNOWN TAROT, inicie a tiragem, revele uma carta e embaralhe novamente.
4. Abra os créditos por teclado e confira a seção da Leo’s House. Use “Voltar à Bomba Land” para retornar ao mapa.

Os smoke tests cobrem fluxos selecionados. Não equivalem a uma auditoria completa de acessibilidade, não validam todas as combinações de navegador e leitor de tela e não incluem reprodução integral do Spotify.
