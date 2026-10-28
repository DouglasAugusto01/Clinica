# Rosely Girardin — Terapeuta Holística

Landing page estática para Rosely Girardin, Facilitadora e Terapeuta Holística
especializada em Barra de Access, Access Facelift, Cerimônia CCU, ThetaHealing e MTVSS.

🔗 **Site publicado:** https://douglasaugusto01.github.io/Clinica/

## Stack

HTML5, CSS3 e JavaScript puro (sem frameworks, sem build step) — pensado para
publicação direta no GitHub Pages.

```
.
├── index.html          # Estrutura e conteúdo da página
├── style.css           # Estilos e responsividade
├── script.js           # Menu mobile, scroll suave, validação do formulário
├── assets/images/      # Logo e demais imagens
├── robots.txt
└── sitemap.xml
```

## Rodando localmente

Não há dependências nem build. Basta abrir `index.html` no navegador, ou
servir a pasta com qualquer servidor estático:

```bash
npx serve .
```

## Formulário de contato

O site não tem backend. Ao enviar, o formulário valida os campos no
navegador e abre uma conversa no WhatsApp com os dados preenchidos
(usando o número definido em `WHATSAPP_NUMBER` em `script.js`).

## Pendências (TODO)

- [ ] Substituir o telefone/WhatsApp placeholder `(21) 99999-9999` pelo número real
      (em `index.html` e na constante `WHATSAPP_NUMBER` de `script.js`).
- [ ] Substituir o e-mail placeholder `contato@roselygirardin.com`.
- [ ] Adicionar os links reais de Facebook/Instagram no rodapé.

## Deploy

O site é publicado automaticamente via **GitHub Pages**, a partir da branch
`main`, pasta raiz (`/`).
