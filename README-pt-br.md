# ddd-ubiquitous-language

## Glossário 

**Cliente**: Pessoa que irá realizar o pedido do seu lanche através do totem de auto-atendimento.

**CPF**: Documentação de identificação do cliente.

**Produto**: Informações do lanche. Exemplo: Hamburguers, Batatas fritas, Refrigerante, etc...

**Cupom**: O Cupom permite um desconto através de um código no totem de auto-atendimento.

**Pedido**: Informa a lista de produtos escolhidos pelo cliente, e suas respectivas informações.

**Comanda**: Informa a lista de produtos escolhidos pelo cliente, e suas respectivas informações. (Pela visão da cozinha).

**Cupom Fiscal**: Informa a lista de produtos escolhidos pelo cliente, e suas respectivas informações. (Pela visão do cliente).

**Código Verificador**: Este código de verificação permite que o cliente consiga resgatar o lanche quando estiver pronto. OBS.: Sem este código, não é possível pegar o lanche com o atendente.

**Status**: Representa o status atual do pedido.

- **Pago:** O pagamento do pedido foi aceito e pago com sucesso;
- **Cancelado**: O pagamento do pedido não foi aceito, então o pedido foi cancelado;
- **Recebido**: O pedido foi recebido pelos cozinheiros;
- **Em progresso**: A preparação do pedido foi iniciada pelos cozinheiros;
- **Pronto**: O pedido está pronto para ser resgatado pelo cliente;
- **Finalizado**: O cliente já resgatou seu lanche.

**Lanche**: A representação real dos items do pedido que foram preparados pelos cozinheiros e pode ser pego pelos clientes.
