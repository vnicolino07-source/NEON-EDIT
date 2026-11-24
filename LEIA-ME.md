# Landing page do NEON EDIT

Publicada no Netlify (neon-edit.netlify.app) a partir deste repositório. Cada commit na branch `main` entra no ar sozinho.

- `index.html`: página atual, a oferta original do NEON EDIT a R$ 47,90, com Meta Pixel (PageView, ViewContent e InitiateCheckout nos botões). Vídeos na raiz (`vsl-neon-edit.mp4`, `exemplo-*.mp4`).
- `oferta-cortes.html`: a página da campanha de cortes (R$ 19,90), guardada para consulta. Fonte editável em `cortes/fonte.html`; vídeos em `media/`, imagens em `img/`.
- `vsl-neon-edit.mp4`, `exemplo-apresentador.mp4`, `exemplo-narrado.mp4`: os vídeos, na mesma pasta do index.
- Checkout: constantes `CHECKOUT_URL` e `OFERTA` (valor do Pixel) no fim do `index.html` (usada pelos botões com `data-checkout`).
- Botão do topo e botão fixo do celular levam até `#oferta`; só os botões da oferta e do encerramento vão para o checkout.

## Página atual (desde 23/11/2026)
- `index.html`: oferta "Você escolhe o tema. O vídeo sai pronto." (vídeos animados por tema), R$ 47, Meta Pixel 1485164890164104, checkout em `CHECKOUT_URL`. Fonte editável em `/home/claude/lp-tema/src.html` (build.py). Vídeos em `media/tema/`.
- `oferta-editor.html`: a oferta anterior do editor (R$ 47,90), guardada.
- Entregas: `entrega/381bfdcb12a4/NEON-EDIT.zip` (kit de vídeos por tema), `entrega/934bd2c830ca/NEON-EDIT.zip` (cortes de live, compradores antigos).
- 24/11/2026: `index.html` passou a ser a versão B ("Uma frase e o seu vídeo sai pronto", 3 usos: perfil, empresa, clientes; VSL `media/tema/vsl-b.mp4`). Fonte: `/home/claude/lp-tema/src-b.html` (build-b.py). A versão A ficou em `oferta-tema-a.html`.

