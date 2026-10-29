# getvila.app

Site do Vila: https://getvila.app (o domínio fica no arquivo `CNAME`; o DNS está na GoDaddy)

Página estática, sem build. Tudo está no `index.html` (estilo e script inline); as imagens ficam em
`img/` e as fontes em `fonts/`. O GitHub Pages publica a branch `main` direto da raiz.

- **Baixar para Mac** aponta para o último release de
  [`getvilaapp/vila-desktop`](https://github.com/getvilaapp/vila-desktop/releases/latest)
  (`Vila-mac.dmg`), então não precisa mudar a cada versão.
- **Imagens:** a arte em pixel é a do jogo (pacotes da LimeZu, os mesmos do app). As cenas de mapa
  saem dos mapas gerados no repositório do Vila.
- **Fontes:** Atkinson Hyperlegible Next e Departure Mono, ambas na SIL Open Font License (`fonts/OFL-*.txt`).
- **Movimento:** as cenas com rolagem respeitam o "reduzir movimento" do sistema; nesse caso cada
  uma aparece parada, no estado final.

Para ver localmente: `python3 -m http.server` na raiz e abra http://localhost:8000.
