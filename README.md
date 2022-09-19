# Banco de dados: Loja

![Modelo do banco de dados da loja de miniaturas](Database-Schema.png)

O modelo presente na figura acima refere ao de uma loja de miniaturas de veículos.
Este modelo possui as seguintes tabelas:

- Customers: armazena dados dos clientes.
- Products: armazena a lista de miniaturas disponíveis.
- ProductLines: armazena dados das categorias das miniaturas.
- Orders: armazena os pedidos realizados pelos clientes.
- OrderDetails: armazena os detalhes da quantidade e valor pedido para cada produto em um pedido.
- Payments: armazena os pagamentos realizados por cada cliente.
- Employees: armazena as informações relacionadas aos funcionários da empresa de vendas.
- Offices: armazena as informações relacionadas aos escritórios da loja.

Utilizando este modelo como base, implemente as seguintes consultas em seus dados:

1. Selecione o último nome de todos os empregados
1. Selecione o último nome, primeiro nome, e cargo de todos os empregados
1. Selecione o primeiro e último nome de todos os empregados, ordenados pelo último nome
1. Selecione todos os empregados que são representantes de venda (Sales rep)
1. Selecione todos os empregados que não são representantes de venda e estão lotados no escritório de código 1
1. Selecione o nome e telefone dos clientes que possuem limite de crédito entre 50.000 e 100.000
1. Selecione todos os funcionários que são VP na empresa
1. Selecione o nome e cargo dos funcionários que não possuem chefe na empresa
1. Selecione os clientes que sejam da França ou Estados Unidos
1. Selecione os nomes dos produtos junto de seu texto de descrição
1. Selecione os empregados que estejam lotados em escritórios dos Estados Unidos
1. Selecione os pedidos realizados por clientes da França
1. Selecione o número e data do pedido, junto da quantidade e nome dos produtos pedidos
1. Selecione os clientes que ainda não realizaram nenhum pedido
1. Selecione o nome dos empregados junto do nome de seus superiores
1. Selecione a quantidade de pedidos realizados por status
1. Selecione o valor total de cada pedido
1. Selecione a quantidade de pedidos realizados por ano
1. Selecione a quantidade de pedidos realizados e entregues por ano
1. Selecione a quantidade de pedidos realizados cujo valor total seja superior a 100.000 
1. Selecione os pedidos que tiveram mais de 200 itens encomendados, ordenados pela quantidade de itens
1. Selecione os pedidos que tiveram mais de 500 itens encomendados e que custaram mais de 60.000, ordenados pela quantidade
