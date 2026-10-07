# DuoOdonto

Site estático (HTML + CSS + JS), sem build.

## Rodar em localhost:3000
Opção 1 (Node): `npm start`
Opção 2 (Python): `python3 -m http.server 3000`
Abra http://localhost:3000

## GitHub
git init && git add . && git commit -m "DuoOdonto" && git branch -M main
git remote add origin SEU_REPOSITORIO && git push -u origin main

## Vercel
Importe o repositório em vercel.com/new. Framework: **Other**. Sem build command e sem output directory. Deploy.

## Editar
- Textos e cores: `index.html` (cores no `:root`).
- Fotos: pasta `images/` (mantenha os mesmos nomes ou ajuste no HTML).
- WhatsApp: atributos `data-n` (número) e `data-m` (mensagem) dos botões.
