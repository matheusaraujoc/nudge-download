# Site do nudge (protótipo)

Página estática única (`index.html`), sem build. Abra direto no navegador para testar.

## Instalador

O botão aponta para `downloads/Nudge-Setup-1.5.3.exe`. Copie o instalador gerado pelo Inno Setup
(`build/installer/`) para `site/downloads/`.

- Cloudflare Pages limita cada arquivo a 25 MB; o GitHub não aceita arquivos acima de 100 MB no repositório.
  Se o instalador passar disso, publique-o em um GitHub Release e troque os dois `href` do botão pelo link do release.

## Publicar

- **GitHub Pages:** Settings → Pages → publicar a pasta `site/` (via Actions) ou mover o conteúdo para `docs/`.
- **Cloudflare Pages:** `npx wrangler pages deploy site` ou conectar o repositório com "Build output directory" = `site`.
