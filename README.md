# NexumCell — Portal do Vendedor

Nova venda, acompanhar aprovação, contrato com assinatura na tela e QR code de instalação da trava.

## Arquivos
- `index.html` — o portal (não precisa mexer).
- `nexumcell-config.js` — **cole aqui o `firebaseConfig`** do projeto NexumCell e os endereços dos portais. Use o **mesmo conteúdo** em todos os repositórios NexumCell.

## Publicar (GitHub Pages)
1. Estes arquivos ficam no repositório `nexumrh/vendedor`.
2. *Settings → Pages → Branch: main / (root) → Save*.
3. Endereço: `https://nexumrh.github.io/vendedor/` (ou domínio próprio em *Custom domain*).
4. No Firebase: *Authentication → Configurações → Domínios autorizados* → adicione o domínio.

Sem `apiKey` no config, o portal abre em **modo demonstração** (dados de exemplo só no navegador).
