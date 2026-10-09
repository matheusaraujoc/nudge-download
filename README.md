# ◈ nudge · pensamento visual

> Pense no espaço, não em listas.

O **nudge** é um canvas infinito para notas, conexões e territórios de ideias. Funciona offline,
guarda tudo na sua máquina e transforma suas notas em flashcards com IA.

Este repositório contém o **site de download** e os **instaladores oficiais** (em
[Releases](https://github.com/matheusaraujoc/nudge-download/releases)). O código-fonte do app não está aqui.

## Download

**[⬇ Baixar nudge 1.5.3 para Windows](https://github.com/matheusaraujoc/nudge-download/releases/download/1.5.3/Nudge-Setup-1.5.3.exe)**
· Windows 10/11 64-bit · ~27 MB · gratuito

1. Baixe e execute o `Nudge-Setup-1.5.3.exe`.
2. Se o Windows SmartScreen avisar, clique em "Mais informações" → "Executar assim mesmo".
3. Abra o nudge pelo menu Iniciar.

Seus dados ficam em `~/.nudge2/nudge.db` (SQLite local). Para fazer backup, copie essa pasta.

## Por que o nudge

- **Espacialidade:** você lembra melhor de uma ideia quando ela tem um lugar fixo.
- **Conectividade:** o valor está nos links entre as ideias, não em notas isoladas.
- **Offline-first:** sem conta, sem nuvem, sem assinatura. Seus dados não saem da sua máquina.

## Recursos

- **Canvas infinito:** arraste, aproxime e organize notas em territórios coloridos. Desfazer e refazer em tudo.
- **Notas ricas:** texto com imagens e blocos de código, checklists com progresso e mini-kanban dentro de cada nota.
- **Conexões inteligentes:** curvas que se ajustam sozinhas, links de mão dupla em paralelo e rótulos nas linhas.
- **Busca global:** encontre qualquer termo em textos, checklists e kanbans de todos os quadros. O canvas "voa" até o resultado.
- **Flashcards com IA:** gere cartões a partir das suas notas com o Gemini e exporte para o Anki.
- **Modo Fantasma:** deixe o quadro semitransparente por cima de aulas, PDFs e vídeos.
- **Exportação:** PNG em alta resolução e PDF recortado exatamente no conteúdo.

## Atalhos principais

| Ação | Atalho |
| :--- | :--- |
| Nova nota | Duplo-clique no canvas ou `Ctrl+N` |
| Nota filha conectada | `Tab` (com uma nota selecionada) |
| Busca global | `Ctrl+K` |
| Mover o canvas | Arrastar com o botão direito ou do meio |
| Zoom | Roda do mouse |
| Abas do editor (Texto / Checklist / Kanban) | `Ctrl+1` / `Ctrl+2` / `Ctrl+3` |

---

## Manutenção do site

Página estática única ([index.html](index.html)), sem build e sem JavaScript. Abra direto no navegador para testar.

**Nova versão:** crie um Release com a tag da versão, anexe `Nudge-Setup-<versão>.exe` e atualize a versão
no `index.html` (links dos botões, linha do hero, seção de download e rodapé) e neste README.

**Publicar:**
- **GitHub Pages:** Settings → Pages → Deploy from branch `main` / raiz.
- **Cloudflare Pages:** conectar o repositório, sem comando de build, output directory = `/`.

## Licença

Software proprietário. Todos os direitos reservados © Matheus Araujo.
