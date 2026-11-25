# Página de compartilhamento — Guia de Acesso à Insulinoterapia | Pará

Página estática (GitHub Pages) que gera a prévia do link no WhatsApp
(título, descrição e imagem via Open Graph) e redireciona a pessoa para o
guia no Apps Script. O Apps Script não aceita essas meta tags na página
dele, por isso esta página existe separada.

- **Link para compartilhar:** https://iurycf.github.io/guia-insulina/
- **App (destino do redirecionamento):** https://script.google.com/macros/s/AKfycbyvGOSV1C68v04811hsVv0m9Bkb9KnFqCmWnmpCZ3S8wq19XDq6Us3FeMZqfxPMHZPpZQ/exec

## Arquivos

- `index.html` — meta tags Open Graph/Twitter + redirecionamento automático
- `og-image.png` — imagem de capa 1200×630 exibida na prévia do link

## Testar a prévia

O WhatsApp guarda a prévia em cache. Depois de qualquer mudança, teste com
um parâmetro novo no final do link, por exemplo `?v=2`.
