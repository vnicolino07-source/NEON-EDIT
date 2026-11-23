# Landing page do NEON EDIT

Publicada no Netlify (neon-edit.netlify.app) a partir deste repositório. Cada commit na branch `main` entra no ar sozinho.

- `index.html`: página atual, a oferta original do NEON EDIT a R$ 47,90, com Meta Pixel (PageView, ViewContent e InitiateCheckout nos botões). Vídeos na raiz (`vsl-neon-edit.mp4`, `exemplo-*.mp4`).
- `oferta-cortes.html`: a página da campanha de cortes (R$ 19,90), guardada para consulta. Fonte editável em `cortes/fonte.html`; vídeos em `media/`, imagens em `img/`.
- `vsl-neon-edit.mp4`, `exemplo-apresentador.mp4`, `exemplo-narrado.mp4`: os vídeos, na mesma pasta do index.
- Checkout: constantes `CHECKOUT_URL` e `OFERTA` (valor do Pixel) no fim do `index.html` (usada pelos botões com `data-checkout`).
- Botão do topo e botão fixo do celular levam até `#oferta`; só os botões da oferta e do encerramento vão para o checkout.
