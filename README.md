# Portfólio · Erick Marcelo

Portfólio de desenvolvimento web em HTML, CSS e JavaScript puros, sem build e sem dependências. Os únicos recursos externos são as fontes do Google Fonts, então abra com internet para ver a tipografia correta.

## Estrutura

```
portfolio-erick/
├── index.html                  página principal (projetos, sobre, contato)
├── projetos/
│   ├── forno-e-brasa.html      site de pizzaria (cardápio filtrável + reserva)
│   ├── argila.html             loja de cerâmica (sacola funcional)
│   └── clinica-mar.html        site de clínica (agendador em passos)
└── README.md
```

Os três projetos são demonstrações com marcas, endereços e preços fictícios.

## Ver no computador

1. Abra a pasta no VS Code (`Arquivo > Abrir Pasta`).
2. Instale a extensão **Live Server** (Ritwick Dey).
3. Clique com o botão direito em `index.html` e escolha **Open with Live Server**.

Também funciona dando dois cliques em `index.html`.

## Subir no GitHub

Crie um repositório vazio no GitHub (por exemplo `portfolio`), sem README, e rode na pasta do projeto:

```bash
git init
git add .
git commit -m "Primeira versão do portfólio"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/portfolio.git
git push -u origin main
```

Troque `SEU-USUARIO` pelo seu usuário do GitHub.

## Publicar e compartilhar o link (GitHub Pages)

1. No repositório, abra **Settings > Pages**.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)` e clique em **Save**.
4. Depois de um ou dois minutos o site fica em `https://SEU-USUARIO.github.io/portfolio/`.

Se nomear o repositório como `SEU-USUARIO.github.io`, o endereço passa a ser `https://SEU-USUARIO.github.io/`.

## O que editar

- **Textos de apresentação**: seção "Sobre" e "Como trabalho" em `index.html`.
- **Contatos**: seção `#contato` em `index.html`. O link do WhatsApp usa o formato `https://wa.me/55DDDNUMERO`.
- **Novos projetos**: copie um bloco `<a class="proj">` em `index.html` e crie a página em `projetos/`.
- **Cores e fontes**: variáveis no início do `<style>` de cada página (`:root`).

## Atualizar depois

```bash
git add .
git commit -m "Descreva a mudança"
git push
```
