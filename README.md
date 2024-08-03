# Cardápio Digital Interativo - AV1 Lanches

Este projeto é um sistema mockado de cardápio digital interativo desenvolvido para uma atividade da faculdade. Utiliza HTML, CSS e JavaScript para criar uma interface responsiva que permite aos usuários selecionar itens, gerenciar o carrinho e finalizar o pedido com diferentes opções de pagamento.

## Estrutura do Projeto

### Apresentação do Cardápio
- **Categorias**: Os itens são organizados em três categorias principais: Hambúrgueres Artesanais, Salgados e Bebidas.
- **Itens do Cardápio**: Cada item possui uma descrição, um preço e um checkbox para seleção. Os itens selecionados são adicionados ao carrinho.

### Gerenciamento do Pedido
- **Carrinho de Compras**: Mostra os itens selecionados, a quantidade de cada um e o total acumulado. Inclui botões para aumentar ou diminuir a quantidade dos itens.
- **Formulário de Finalização do Pedido**: Coleta informações do cliente, como nome completo e endereço. Aparece após o cliente clicar em "Finalizar Pedido".

### Finalização do Pedido
- **Método de Pagamento**: Oferece várias opções, incluindo Cartão de Crédito, Débito e PIX.
- **Detalhes de Pagamento**: Campos adicionais são exibidos para coleta de informações relevantes dependendo do método de pagamento selecionado.
- **Resumo do Pedido**: Mostra os detalhes finais do pedido para confirmação, incluindo os itens selecionados, total do pedido e informações do cliente.

## Tecnologias Utilizadas

- **HTML**: Para a estrutura da interface.
- **CSS**: Para a estilização da interface.
- **JavaScript (jQuery)**: Para a manipulação do DOM e interatividade.

## Funcionalidades

- **Adição e Remoção de Itens**: Adicione ou remova itens do carrinho clicando nas checkboxes.
- **Controle de Quantidade**: Aumente ou diminua a quantidade dos itens diretamente no carrinho.
- **Finalização do Pedido**: Insira informações do cliente e escolha o método de pagamento para finalizar o pedido.
- **Modal de Confirmação**: Exibe uma confirmação antes de finalizar o pedido.

## Como Usar

1. **Abra o arquivo HTML em um navegador** para visualizar a interface do cardápio.
2. **Selecione os itens do cardápio** usando as checkboxes e ajuste as quantidades conforme necessário.
3. **Clique em "Finalizar Pedido"** para revisar o carrinho e prosseguir com a inserção das informações do cliente e detalhes de pagamento.
4. **Escolha o método de pagamento** e forneça as informações necessárias. Para pagamentos via Pix, um QR Code será gerado.
5. **Confirme o pedido** após revisar o resumo.
