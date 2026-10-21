# Espresso English — Grammar Studio

Plataforma de conteúdo da marca própria (Espresso English) para o material de Grammar.

- **Arquivo único**: `index.html` (HTML + CSS + JS + conteúdo embutidos, sem dependências locais)
- **Logo oficial** embutido (data URI) — funciona offline, sem pastas ao lado
- **Conteúdo**: 15 categorias · 53 conjuntos de prática · 396 questões
- **Lesson / Explanation** antes de cada prática; áreas Professor e Aluno
- **Gerar PDF**: folha A4 com o logo (usa html2pdf via CDN; sem internet cai em Imprimir → Salvar como PDF)

## Como atualizar
1. Substitua o `index.html` pela versão nova.
2. `git add index.html && git commit -m "Atualiza plataforma" && git push`
3. O GitHub Pages publica sozinho em ~1 minuto.

## Publicação
GitHub Pages → branch `main` → pasta `/ (root)`.
