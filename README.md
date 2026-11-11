# Cupom do Dia

Porta de entrada do site Cupom do Dia na Netlify.

- `index.html`: página com o ícone do site e o botão "Ver cupons de hoje". Quando aberta pelo ícone da Tela de Início, vai direto para os cupons.
- Os cupons ficam em https://claude.ai/artifact/QZFC3qJEpP2kDVktxdPvFC, atualizado a cada 3 horas por uma tarefa agendada do Claude. Esta página não precisa mudar quando os cupons mudam, então não gasta deploys da Netlify.
- `icons/`: favicon e ícone da Tela de Início (iPhone e Android).
- Ramo `dados`: lista antiga de cupons, não é mais usada.
