# Lymphoria — fretes antes do endereço

Publicado em 28/11/2026 nos checkouts Reign 26037 (avulso) e 26038 (assinatura).

Os dois fretes agora aparecem com os campos de endereço vazios: Free Shipping US$0.00 e Paid Shipping — Lymphoria US$4.95. É possível pré-selecionar uma opção.

A API nativa da Reign exige cidade e CEP para confirmar as tarifas. A pré-seleção é guardada somente na sessão do navegador e aplicada ao controle nativo assim que o endereço válido é preenchido. O total não é simulado ou alterado por JavaScript; a seleção chama o fluxo nativo da Reign e o servidor retorna o valor real. Uma nota discreta informa que o frete entra no total após o endereço.

## Testes

- Desktop, assinatura de 2 frascos: ambos os fretes visíveis com nome, sobrenome, endereço, cidade e CEP vazios. Pré-seleção paga mantida após preencher o endereço. API set_shipping_method retornou HTTP 200, ShippingMethodID 9241 e total US$59.94 (US$54.99 + US$4.95).
- Celular de 390 px, avulso de 1 frasco: os dois fretes visíveis antes do endereço. Escolha paga trocada para grátis antes de preencher. Após endereço, Free Shipping selecionado e total US$39.99. Página sem overflow.
- Troca manual de frete após o endereço preservada; o script não reaplica uma escolha antiga sobre a seleção nova do cliente.
- Produtos/variantes, preços, plano de renovação de 30 dias e regras de frete comparados ao backup e idênticos. Nenhuma compra finalizada.

## Design preservado

Comparação estrutural das duas páginas confirmou que o restante do design aprovado permanece idêntico. Só o conteúdo anterior ao endereço do componente ShippingMethodSelect, os estilos locais das opções e o comportamento de pré-seleção foram adicionados. Nenhuma configuração de segurança ou de pagamento foi modificada.

## Arquivos

- early-shipping.html: duas opções no placeholder nativo antes do endereço.
- early-shipping.css: reproduz o visual aprovado dos fretes.
- early-shipping.js: Manual Script da Reign, sem chamadas diretas de API, sem mexer em campos de endereço, itens, preços ou totais.

A funcionalidade pressupõe as regras atuais Free Shipping 9222 e Paid Shipping — Lymphoria 9241, com atendimento a endereços elegíveis nos EUA. A confirmação final continua sujeita ao endereço informado.

[Conferir checkout](https://securepayment.shop/pages/checkout-reign?offer=lymphoria-1&mode=sub)
