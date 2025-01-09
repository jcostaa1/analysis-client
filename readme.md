Este projeto tem como objetivo simular uma análise de vendas com uma tabela de dados fictícios. A análise será realizada para responder a várias questões críticas de negócios relacionadas à performance de vendas, como o produto mais vendido, o impacto dos descontos, o desempenho de vendedores e clientes, entre outras. O projeto culminará na criação de um dashboard interativo em Python, fornecendo visualizações dinâmicas para apoiar a tomada de decisões pela equipe de negócios.

Ao final deste projeto, conseguiremos responder as seguintes questões:
1.	Qual é o produto mais vendido em termos de quantidade?
2.	Qual é o produto que gerou mais receita?
3.	Qual o valor total de vendas por produto?
4.	Qual o valor médio de vendas por produto?
5.	Qual é o desconto médio concedido nas vendas?
6.	Qual é o valor total de descontos concedidos?
7.	Quais produtos recebem maiores descontos?
8.	Qual é o vendedor com mais vendas em termos de valor?
9.	Qual é o vendedor com mais vendas em termos de quantidade?
10.	Qual é o valor médio de vendas por vendedor?
11.	Qual é o cliente com mais compras em termos de valor total?
12.	Qual é o cliente com mais compras em termos de quantidade?
13.	Quais são os estados com maior volume de vendas?
14.	Qual é a distribuição de compras por sexo?
15.	Quais são os períodos com mais vendas?
16.	Qual é a variação nas vendas ao longo do tempo?
17.	Qual é o dia da semana com maior volume de vendas?
18.	Qual a margem de lucro média por venda?
19.	Qual é a rentabilidade por produto (ValorTotal - Custo)?

Objetivo principal
Este projeto busca proporcionar uma análise simples e objetiva das vendas, focando em ajudar o time de negócios na tomada de decisões estratégicas.

Estrutura de dados
O projeto utiliza uma tabela simulada de vendas, com os seguintes campos:
ProdutoID: Identificador único do produto.
Produto: Nome do produto vendido.
VendasID: Identificador único da venda.
Quantidade: Quantidade de produtos vendidos.
ValorUnitario: Valor unitário do produto.
ValorTotal: Valor total da venda sem descontos.
Desconto: Valor do desconto concedido na venda.
TotalComDesconto: Valor total da venda após o desconto.
Vendedor: Nome do vendedor responsável pela venda.
ClienteID: Identificador único do cliente.
Data: Data da venda.
Cliente: Nome do cliente.
Estado: Localização do cliente.
Sexo: Sexo do cliente.
Status: Status da venda (ex: realizada, cancelada).

Visão geral das análises
Com base na tabela simulada de vendas, o projeto permite a análise dos seguintes pontos:
Produtos: Desempenho de vendas por produto, impacto dos descontos, rentabilidade por produto.
Vendedores: Performance por vendedor, tanto em termos de quantidade quanto em valor de vendas.
Clientes: Análise de compras por cliente, segmentação por localização (estado) e perfil (sexo).
Tendências Temporais: Análise de variação nas vendas ao longo do tempo, identificando sazonalidades e melhores períodos de vendas.

Tecnologias utilizadas
Python: Linguagem principal para análise e visualização.
Pandas: Manipulação de dados e análise exploratória.
Matplotlib/Seaborn: Visualizações gráficas adicionais.