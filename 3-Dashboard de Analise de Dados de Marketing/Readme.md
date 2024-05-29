# Mini-Projeto de Análise de Campanhas de Marketing com Power BI



Este projeto é uma introdução às práticas de análise de dados utilizando o Power BI, focando especificamente em campanhas de marketing. Serão criados quatro dashboards diferentes, contendo mais de 10 elementos visuais, customizações, formatações, correções nos dados e utilização de diversos recursos do Power BI estudados durante o curso.

Os dados foram para este mini-projeto representam informações sobre clientes e campanhas de marketing realizadas por uma empresa.



## Visões Desenvolvidas

O projeto é dividido em quatro visões principais:

1. **Visão do Cliente**
2. **Visão do Comportamento de Compra do Cliente**
3. **Visão da Performance das Campanhas de Marketing**
4. **Visão dos Padrões de Compra no Ponto de Venda (País)**



### 1. Visão do Cliente

Nesta visão, analisamos o perfil dos clientes, incluindo dados demográficos e outras informações relevantes. Os gráficos e medidas criados aqui ajudam a entender melhor quem são os clientes da empresa.

### 2. Visão do Comportamento de Compra do Cliente

Focamos no comportamento de compra dos clientes, identificando padrões e preferências. Esta análise ajuda a identificar quais produtos são mais populares e quais estratégias de marketing estão funcionando.

### 3. Visão da Performance das Campanhas de Marketing

Analisamos a efetividade das campanhas de marketing realizadas pela empresa. Esta visão permite avaliar o retorno sobre investimento (ROI) e identificar quais campanhas foram mais bem-sucedidas.

### 4. Visão dos Padrões de Compra no Ponto de Venda (País)

Nesta última visão, focamos nos padrões de compra em diferentes pontos de venda, divididos por país. Esta análise ajuda a entender como os clientes em diferentes regiões respondem às campanhas de marketing.



## Medidas e Métricas Utilizadas

Para criar os dashboards e análises, várias medidas e métricas foram criadas no Power BI. Um exemplo de medida criada é a seguinte:

### Medida: Total Gastos

```
Total Gastos = SUMX(
    DadosMarketing, 
    DadosMarketing[Gasto com Alimentos] +
    DadosMarketing[Gasto com Eletronicos] +
    DadosMarketing[Gasto com Moveis] +
    DadosMarketing[Gasto com Utilidades] +
    DadosMarketing[Gasto com Vestuario]
)
```

Esta medida calcula o total de gastos dos clientes, somando os gastos em diferentes categorias de produtos.



## Conclusão

Este mini-projeto oferece uma visão abrangente sobre o perfil dos clientes, os padrões de compra e a efetividade das campanhas de marketing, utilizando diversas funcionalidades do Power BI. 



<img src="https://i.ibb.co/bRY3Hr7/Visao-Clientes.jpg" alt="Visao-Clientes" style="zoom: %;" />

<img src="https://i.ibb.co/r3m5HCX/Visao-Comportamento-Clientes.jpg" alt="VisaoComportamentoCliente" style="zoom:%;" />

<img src="https://i.ibb.co/9YTXg7K/Visao-Campanhas-Realizadas.jpg" alt="CampanhasRealizadas" style="zoom:%;" />

<img src="https://i.ibb.co/s16rf27/Visao-Pontos-Vendas.jpg" alt="Visao-Ponto-Vendas" style="zoom:%;" />









