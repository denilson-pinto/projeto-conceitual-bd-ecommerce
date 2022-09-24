# PROJETO CONCEITUAL E-COMMERCE

## Desafio de projeto do bootcamp Database Experience da Digital Innovation One, com o propósito de refinar um modelo conceitual de banco de dados de um e-commerce.

Pontos de refinamento proposto no desafio:

* **CLIENTE**: foi aplicado a técnica de especialização gerando duas novas entidades, **PESSOA FÍSICA** e **PESSOA JURÍDICA**. Cada uma das duas novas entidades possuem os respectivos atributos peculiares a cada perfil.

* **PAGAMENTO**: foi criada a entidade **TIPO DE PAGAMENTO**, e esta se relaciona com a entidade **PEDIDO**. TIPO DE PAGAMENTO foi especializada em outras duas entidades, **CARTÃO** e **BOLETO**.

* **ENTREGA**: foi criada a entidade **FRETE** que possui os atributos pertinentes a entrega do produto, dentre elas o atributo **Status**. Tal entidade está relacionada à **PEDIDO** e **RASTREIO**.
