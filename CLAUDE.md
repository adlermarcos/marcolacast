# Marcolacast — Wingfoil Forecast App

## Sobre o projeto
App de previsão de condições para wingfoil em HTML único auto-contido.
Usa Open-Meteo API (gratuita, sem key). Tema claro/escuro, mobile-first.

## Arquivo principal
`index.html` — tudo em um único arquivo (HTML + CSS + JS inline).

## Como fazer deploy
Após qualquer alteração no index.html:
git add index.html
git commit -m "feat: descrição da mudança"
git push origin main

O GitHub Actions faz o deploy automaticamente no GitHub Pages.

## URL de produção
https://adlermarcos.github.io/marcolacast/

## Convenções
- Não quebrar o arquivo em múltiplos arquivos
- Manter compatibilidade mobile (viewport meta já configurado)
- Preservar o sistema de temas claro/escuro (data-theme)
- CSS variables em :root e [data-theme="dark"]
