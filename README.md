# Central Boost — Remake

Nova aplicação estática construída do zero a partir do conteúdo e da identidade do projeto original.

## Estrutura

- `index.html` — entrada da aplicação
- `styles.css` — design system e responsividade
- `app.js` — componentes, rotas e filtros
- `content.js` — conteúdo dos tutoriais, separado da interface
- `assets/` — imagens migradas do projeto original

## Adicionar tutorial

Edite `content.js` e adicione um novo objeto ao array `TUTORIALS`. O layout das páginas não precisa ser alterado.

Campos principais: `slug`, `title`, `short`, `category`, `subcategory`, `tags`, `difficulty`, `date`, `videoId`, `steps` e `sections`.

## YouTube

O site recebe somente o `videoId`. O iframe é criado pelo componente de vídeo e carregado sob demanda para evitar carregar o player antes da hora.

## Executar

Por ser uma aplicação estática, pode ser publicada em Netlify, GitHub Pages ou outro host estático. Para desenvolvimento local, um servidor HTTP simples é suficiente.
