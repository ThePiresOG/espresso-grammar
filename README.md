# Espresso English — Grammar Studio

Plataforma de conteúdo da marca própria (Espresso English) para o material de Grammar.
Publicada via **GitHub Pages** com suporte a **PWA** (instalável e offline).

**Site:** https://thepiresog.github.io/espresso-grammar/

## Estrutura
```
index.html              # app completo (HTML + CSS + JS + conteúdo embutidos)
manifest.webmanifest    # identidade do PWA (nome, ícones, atalhos, cores)
sw.js                   # service worker: cache do shell + modo offline
icons/                  # ícones gerados do logo oficial (192, 512, maskable, apple-touch)
.nojekyll               # impede o GitHub de processar como Jekyll
```

## Conteúdo
- 15 categorias · 53 conjuntos de prática · 396 questões
- "Lesson / Explanation" antes de cada prática (aulas com tabelas, erros comuns e dicas)
- Áreas **Professor** (gabarito, notas, erros comuns) e **Aluno** (worksheet)
- **Gerar PDF**: folha A4 com o logo (html2pdf via CDN; sem internet → Imprimir → Salvar como PDF)

## Instalar no celular
- **Android/Chrome:** menu ⋮ → *Instalar app* / *Adicionar à tela inicial*
- **iPhone/Safari:** Compartilhar → *Adicionar à Tela de Início*

## Atualizar
1. Substitua `index.html` pela versão nova (build de 1 arquivo).
2. `git add -A && git commit -m "Atualiza plataforma" && git push`
3. O Pages republica em ~1 min. O `sw.js` usa *network-first* na navegação,
   então a versão nova aparece no próximo acesso com internet.

## Publicação
Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
