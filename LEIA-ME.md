# Landing page do NEON EDIT

Publicada no Netlify (neon-edit.netlify.app) a partir deste repositório. Cada commit na branch `main` entra no ar sozinho.

- `index.html`: página atual (campanha de cortes, R$ 19,90, com Meta Pixel). Fonte editável em `cortes/fonte.html`; vídeos em `media/`, imagens em `img/`.
- `anterior.html`: a página antiga (R$97), guardada para consulta.
- `vsl-neon-edit.mp4`, `exemplo-apresentador.mp4`, `exemplo-narrado.mp4`: os vídeos, na mesma pasta do index.
- Checkout: constante `CHECKOUT_URL` no fim do `index.html` (usada pelos botões com `data-checkout`).
- Botão do topo e botão fixo do celular levam até `#oferta`; só os botões da oferta e do encerramento vão para o checkout.
