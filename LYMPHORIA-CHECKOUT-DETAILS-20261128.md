# Lymphoria — conferência fina do checkout, 28/11/2026

Publicação nas páginas Reign 26037 e 26038. Comparação atual da referência em desktop e celular.

## Ajustes medidos

- Removido o gap indevido da grade: formulário de 500 px e resumo de 400 px, nas mesmas posições horizontais da referência em viewport de 1920 px.
- Fundo creme corrigido para #fef9f2, medido na referência. Texto dos totais e campos em #002514.
- Total com 18 px e peso 600, com indicação USD; pesos dos títulos ajustados, incluindo Delivery de 700 para 600.
- Rótulos flutuantes Country/Region e State nos seletores nativos, sem alterar valores, países ou validações.
- Linha informativa abaixo do total, com garantia de 30 dias e o tipo de compra real: One-time purchase ou Every 30 days.
- Título gráfico original Proven by Experience (192 × 17 px). Cards de avaliações com 176 × 301 px, intervalo de 16 px e rolagem sem barra aparente.
- Botão Secure My Order com 50 px de altura, borda de 16 px, fonte de 14 px/peso 600 e fundo #125e3b.
- Estilos essenciais embutidos no cabeçalho para evitar largura indevida na primeira renderização móvel.

## Preservação e testes

Produtos/variantes, preços, plano Reign AUTOSHIP de 30 dias e todas as regras de frete comparados ao backup anterior e idênticos. Componentes de pagamento e de frete sem mudança de configuração. Nenhuma compra realizada.

Avulso de um frasco: US$39.99 grátis / US$44.94 com frete de US$4.95. Assinatura de dois frascos: US$54.99 grátis / US$59.94 com frete de US$4.95. A linha informativa exibiu corretamente cada tipo de compra.

Celular: 390 px de viewport e conteúdo, um cabeçalho visível e resumo expansível. Campos, rótulos e avaliações revisados.

## Limitações reais

O pagamento permanece no componente nativo Reign/Whop. O checkout Shopify da referência tem recursos próprios de Shop Pay, login e reserva; não foram inseridas imitações. O valor dinâmico continua no resumo nativo, sem valor fixo dentro do botão. Itens, brindes, preços em euros e renovação bimestral da referência não foram importados.

## Fonte

checkout-reference.css, blocos HTML, assets/ e native-presentation-settings.json (somente apresentação). Não substituir o index.html da loja por estes blocos: pertencem ao editor de checkout Reign. Os backups completos ficaram locais e não contêm arquivos publicados neste pacote.

[Conferir checkout](https://securepayment.shop/pages/checkout-reign?offer=lymphoria-1&mode=sub)
