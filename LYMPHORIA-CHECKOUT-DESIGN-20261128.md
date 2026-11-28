# Lymphoria — design do checkout, 28/11/2026

Design aplicado nas páginas Reign 26037 (avulso) e 26038 (assinatura), usando os sete PNGs fornecidos pelo usuário e os três SVGs de serviço da referência.

- Cabeçalho completo com logo e selos: formulário à esquerda no desktop, topo no celular.
- Fundo creme, resumo branco, tons verdes, campos arredondados e botão Secure My Order.
- Garantia de 30 dias e blocos de US Fulfillment, Shipping & Easy Returns e 100,000+ Happy Customers.
- Quatro cards originais de avaliações com rolagem horizontal; imagem adicional de classificação abaixo do botão.
- Imagens hospedadas em https://getlymphorias.shop/assets/checkout-reference-20261128/.

## Preservado e validado

| Frascos por kit | Avulso (US$) | Assinatura (US$) | Total avulso com frete pago | Total assinatura com frete pago |
|---|---:|---:|---:|---:|
| 1 | 39.99 | 34.99 | 44.94 | 39.94 |
| 2 | 79.99 | 54.99 | 84.94 | 59.94 |
| 3 | 99.99 | 79.99 | 104.94 | 84.94 |

As seis combinações foram abertas no checkout e testadas com Free Shipping (US$0.00) e Paid Shipping — Lymphoria (US$4.95), em endereço elegível nos EUA. Nenhuma compra foi finalizada.

Variantes Shopify, plano Reign AUTOSHIP 2509 com renovação de 30 dias e todas as regras de frete foram comparados antes/depois e permaneceram idênticos. Componentes de carrinho, formulário de entrega, seletor de frete, pagamento Whop, totais e termos foram preservados. Somente layout, imagens, cores e texto do botão mudaram. Outros produtos não foram alterados.

Verificação visual em desktop e celular de 390 px; sem overflow da página. Resumo móvel expansível e acesso às quatro avaliações confirmados. As imagens fornecidas foram aplicadas sem redesenho nem remoção de texto.

## Limites da adaptação

O pagamento continua no componente seguro nativo da Reign/Whop, com os métodos disponíveis nessa integração. Não foram criados botões falsos de Shop Pay ou Google Pay nem uma reserva de estoque fictícia. Itens extras, preço em euros e renovação bimestral da referência não foram importados.

## Arquivos do pacote

- checkout-reference.css: estilos completos da página na Reign.
- checkout-desktop-header.html e checkout-mobile-header.html.
- checkout-trust.html: garantia, ícones e avaliações.
- checkout-rating.html: imagem adicional de avaliação.
- assets/: arquivos PNG/SVG originais hospedados no domínio.

Os HTMLs são blocos CustomHTML dentro do editor Reign, não uma substituição do index.html da loja. Backup das configurações anteriores foi mantido localmente. Nenhuma credencial ou dado de cliente está incluído.

[Conferir checkout — 2 frascos, assinatura](https://securepayment.shop/pages/checkout-reign?offer=lymphoria-1&mode=sub)
