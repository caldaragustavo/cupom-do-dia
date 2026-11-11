# Cupom do Dia

Site estático com cupons de desconto e frete grátis de AliExpress, Mercado Livre, Shopee e Amazon.

- `index.html`: a página. Ela lê `coupons.json` ao abrir.
- Cupons: a lista oficial fica em `coupons.json` no ramo **dados**. Uma tarefa agendada do Claude atualiza esse ramo a cada 3 horas. A página lê o arquivo direto do GitHub, então atualizar os cupons não gera deploy na Netlify (cada deploy gasta créditos do plano grátis).
- `coupons.json` (neste ramo main): cópia de reserva, usada só se o GitHub não responder.
- `icons/`: ícone do site (favicon e ícone da Tela de Início do iPhone/Android).

Não precisa de build: na Netlify, deixe o comando de build vazio e a pasta de publicação como a raiz (`/`).
