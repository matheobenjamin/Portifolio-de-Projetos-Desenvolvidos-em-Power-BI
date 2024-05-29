# **Dashboard de Vendas , Custo, Margem de Lucro e KPI**



Este projeto envolve a análise de dados de vendas para responder a várias perguntas de negócios usando diferentes tipos de visualizações. O objetivo é obter insights sobre o desempenho das vendas, custos de envio e lucratividade, que são cruciais para a tomada de decisões estratégicas. 



Nosso Dashboard deve responder as perguntas abaixo:

- Qual foi o total de valor venda considerando cada modo de envio dos pedidos? 
- Quais mercados tiveram o maior custo médio de envio dos produtos vendidos?
- A empresa tem como objetivo (meta) manter uma média de 350 para o valor de venda todos os meses. Mostre um indicador (KPI–Key Performance Indicator) com o valor médio de venda. A empresa ficou abaixo ou acima da meta no mês de Abril/2014?
- Considere que o lucro é equivalente a : valor venda \- custo envio . Qual categoria de produto apresentou maior lucro médio?
- Qual foi o comportamento da margem de lucro ao longo do tempo? Considere a margem de lucro como o lucro dividido pelo valor venda.



Foi criada as seguintes expressões em Dax para que fosse realizado as respostas das perguntas

- Lucro = Vendas[Valor Venda] - Vendas[Custo Envio] 
- Margem Lucro = ROUND(DIVIDE(Vendas[Lucro], Vendas[Valor Venda]) * 100,2)



![Dashboard-de-Vendas-Custo-Margem-de-Lucro-e-KPI](https://i.ibb.co/h7m6NBm/Dashboard-de-Vendas-Custo-Margem-de-Lucro-e-KPI.jpg)