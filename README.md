# Minha grade ABENEPI 2026

Site estático para montar sua grade pessoal de palestras do VIII Congresso Internacional e XXVIII Brasileiro da ABENEPI (Natal, 28 a 31 de outubro de 2026).

Tudo roda no navegador, sem servidor: `index.html` contém a programação completa e o aplicativo. A seleção fica salva no próprio aparelho (localStorage).

## Publicar no GitHub Pages

1. Crie um repositório novo (por exemplo `abenepi-2026`).
2. Envie o arquivo `index.html` para a raiz do repositório.
3. Em **Settings > Pages**, escolha *Deploy from a branch*, branch `main`, pasta `/ (root)`.
4. Em um ou dois minutos o site fica no ar em `https://SEU-USUARIO.github.io/abenepi-2026/`.

## Funções

- Grade completa por dia, agrupada por horário e sala
- Busca por tema, palestrante ou sala
- Seleção com aviso de conflito de horário
- Minha agenda: lista cronológica das escolhas
- Compartilhar: link com a agenda embutida (quem abre pode importar)
- Copiar texto pronto para WhatsApp
- Exportar .ics para Google Calendar / Apple Calendar
- Imprimir ou salvar em PDF

## Atualizar a programação

A programação está embutida no `index.html` dentro da tag `<script id="data" type="application/json">`. O arquivo `programacao.json` é a mesma informação em formato editável.
