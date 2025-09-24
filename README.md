# Projeto Interface — Reconstrução de telas

## Páginas implementadas
- index.html — Home
- listagem.html — Listagem de itens
- detalhe.html — Detalhe do item

## Estrutura do repositório
- index.html, listagem.html, detalhe.html
- /css/styles.css
- /assets (imagens e ícones)
- README.md

## Decisões de layout
- Mobile-first
- Layout: Grid para cards; Flexbox para header/nav
- Tipografia: escala em rem (h1 = 2.5rem; body = 1rem)
- CSS organizado em variáveis (:root) para cores e espaçamentos

## Breakpoints usados
- 481px — celulares grandes
- 768px — tablets
- 1024px — desktops

## Acessibilidade
- `alt` em todas as imagens não decorativas
- Labels vinculados a inputs
- `skip-link` para navegação direta
- Foco visível com outline
- Contraste conforme WCAG AA

## Observações
- Assets em /assets (use placeholders inicialmente)
- Para visualizar: abra index.html no navegador
