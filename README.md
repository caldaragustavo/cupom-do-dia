# Cupom do Dia

Site estático com cupons de desconto e frete grátis de AliExpress, Mercado Livre, Shopee e Amazon.

- `index.html`: a página. Ela lê `coupons.json` ao abrir.
- `coupons.json`: a lista de cupons. Uma tarefa agendada do Claude reescreve esse arquivo todo dia de manhã e faz commit aqui; a Netlify republica sozinha a cada commit.
- `icons/`: ícone do site (favicon e ícone da Tela de Início do iPhone/Android).

Não precisa de build: na Netlify, deixe o comando de build vazio e a pasta de publicação como a raiz (`/`).
