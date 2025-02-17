## *__Análise de vendas com gráficos em Python__*

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
14.	Qual é a distribuição de compras por gênero?
15.	Quais são os períodos com mais vendas?
16.	Qual é a variação nas vendas ao longo do tempo?
17.	Qual é o dia da semana com maior volume de vendas?
18.	Qual é a rentabilidade por produto?

## *__Objetivo principal__*

Este projeto busca proporcionar uma análise simples e objetiva das vendas, focando em ajudar o time de negócios na tomada de decisões estratégicas.

## *__Estrutura de dados__*

O projeto utiliza uma tabela simulada de vendas, com os seguintes campos:
- _Data_: Data da venda.
- _VendasID_: Identificador único da venda.
- _ProdutoID_: Identificador único do produto.
- _Produto_: Nome do produto vendido.
- _Quantidade_: Quantidade de produtos vendidos.
- _ValorUnitario_: Valor unitário do produto.
- _ValorTotal_: Valor total da venda sem descontos.
- _Desconto_: Valor do desconto concedido na venda.
- _TotalComDesconto_: Valor total da venda após o desconto.
- _Vendedor_: Nome do vendedor responsável pela venda.
- _ClienteID_: Identificador único do cliente.
- _Cliente_: Nome do cliente.
- _Estado_: Localização do cliente.
- _Sexo_: Sexo do cliente.
- _Status_: Status da venda (ex: realizada, cancelada).

## *__Visão geral das análises__*

Com base na tabela simulada de vendas, o projeto permite a análise dos seguintes pontos:
- _Produtos_: Desempenho de vendas por produto, impacto dos descontos, rentabilidade por produto.
- _Vendedores_: Performance por vendedor, tanto em termos de quantidade quanto em valor de vendas.
- _Clientes_: Análise de compras por cliente, segmentação por localização (estado) e perfil (sexo).
- _Tendências Temporais_: Análise de variação nas vendas ao longo do tempo, identificando sazonalidades e melhores períodos de vendas.

## *__Tecnologias utilizadas__*

- _Python_: Linguagem principal para análise e visualização.
- _Pandas_: Manipulação de dados e análise exploratória.
- _Matplotlib_: Visualizações gráficas adicionais.