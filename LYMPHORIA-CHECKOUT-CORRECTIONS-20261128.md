# Correções visuais do checkout Lymphoria — 28/11/2026

Comparação direta do checkout Reign com a referência lymphoria.co em desktop e celular.

## Erros encontrados e corrigidos

- A regra genérica de transparência atingia inputs e os indicadores de frete. Foi restrita aos elementos de texto. Campos brancos e círculo verde do frete selecionado restaurados.
- Fundos brancos indevidos dos títulos retirados por configuração dos blocos de texto, sem apagar fundos dos controles.
- Cabeçalhos configurados por dispositivo e dimensões essenciais colocadas diretamente no HTML das imagens, evitando cabeçalho duplicado ou imagens gigantes no carregamento.
- Miniatura reduzida para 64 px; quantidade real exibida em selo legível; nome com peso normal e variante em texto secundário.
- Controles de aumentar/remover kit retirados da apresentação do resumo para corresponder à referência. Nenhuma quantidade de carrinho foi alterada.
- Campo de cupom nativo da Reign exibido no resumo, sem criar cupom ou aplicar desconto.
- Alinhamento, espaçamento superior, cabeçalho móvel e acabamento do cupom ajustados.

## O que foi preservado

Itens e variantes Shopify idênticos ao backup anterior. Preços por kit: avulso US$39.99 / US$79.99 / US$99.99; assinatura US$34.99 / US$54.99 / US$79.99. Plano Reign 2509, renovação de 30 dias e todas as regras de frete comparados e sem mudanças. Dois checkouts publicados: 26037 e 26038.

Validação do avulso de 1 frasco: US$39.99 com frete grátis e US$44.94 com frete pago. Assinatura de 2 frascos: US$54.99 e US$59.94. Indicador nativo confirma o método selecionado. Nenhuma compra foi finalizada.

Celular: 390 px de viewport e 390 px de conteúdo, um único cabeçalho visível, resumo expansível, miniatura, cupom e avaliações acessíveis.

## Diferenças reais da referência

A referência usa o checkout Shopify com Shop Pay, Google Pay e mensagem de reserva. A integração atual utiliza o componente de pagamento Reign/Whop. Não foram inseridos botões falsos ou contador fictício. A referência também contém brinde e moeda/recorrência diferentes; essas condições não foram copiadas. Assim, a posição vertical de alguns blocos difere pelo conteúdo real do pedido.

## Arquivos

checkout-reference.css, checkout-desktop-header.html, checkout-mobile-header.html, checkout-trust.html, checkout-rating.html e assets/. Estes são os blocos da página Reign; não substituem o index.html da loja.

Configurações de apresentação nativas alteradas no Cart: showQuantityButtons=false, hideCloseButton=true, cores e fontes. PromoCode do resumo: visível em desktop/tablet/mobile, campo sem título redundante. Backups completos mantidos localmente, fora do pacote público.

[Conferir checkout atualizado](https://securepayment.shop/pages/checkout-reign?offer=lymphoria-1&mode=sub)
