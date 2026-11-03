# Painel de Vendas — Oli / CX2

Painel simples para registrar vendas (produto, valor, data). Sem login — quem tiver o link acessa.

Dados salvos no navegador (localStorage) de cada aparelho que acessa — não sincronizam entre celular e PC.

## Subir no GitHub

Dentro desta pasta `Oli`:

```bash
git init
git add .
git commit -m "Painel de vendas"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/painel-vendas.git
git push -u origin main
```

Crie antes o repositório vazio `painel-vendas` no GitHub (sem README).

## Publicar no Render

1. New → Static Site.
2. Conecte o repositório `painel-vendas`.
3. Build Command: deixe vazio.
4. Publish Directory: `.`
5. Create Static Site.

Gera um link tipo `https://painel-vendas.onrender.com`.
