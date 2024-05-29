# Dashboard Logístico com Power BI - Logístico



 O objetivo principal é oferecer uma visão abrangente das operações logísticas de uma empresa de transporte, abordando dados de entregas de produtos (fretes), análise de viagens, informações sobre motoristas e o faturamento da empresa.

## Dados Utilizados

Os dados foram extraídos do arquivo "Base Logística.xlsx", cobrindo o período de 2022 a 2024. Este arquivo serviu como fonte primária para a análise realizada neste projeto.

## Passo a Passo da Construção do Dashboard

1. **Importação da Base de Dados**: Utilizando o Power BI, importamos a base de dados a partir do arquivo Excel. Isso é feito selecionando o ícone "Pasta de trabalho do Excel" no menu da "Página Inicial" e escolhendo o arquivo desejado.
2. **Tratamento de Dados com o Power Query**: No ambiente do Power Query, realizamos os tratamentos necessários na base de dados para prepará-la para uso no Power BI. Isso incluiu a renomeação de colunas, remoção de colunas desnecessárias e linhas em branco, além da divisão de colunas com informações combinadas.
3. **Criação de Visualizações**: Utilizando as funcionalidades do Power BI, criamos visualizações relevantes para representar os dados de forma clara e informativa. Isso incluiu Segmentação de dados, gráficos de barras, tabelas dinâmicas e mapas geográficos, entre outros.
4. **Personalização do Layout**: Para garantir uma experiência visual agradável, personalizamos o layout do dashboard, ajustando cores, fontes e disposição dos elementos.
5. **Publicação e Compartilhamento**: Finalmente, publicamos o dashboard no serviço Power BI para que ele possa ser compartilhado e acessado por outros usuários.



### **Medidas Criadas** 

- Receita = SUM(BaseLogistica[Valor do Frete Líquido])
- Custo Total = SUM(BaseLogistica[Custos])
- Lucro = [Receita] - [Custo Total]
- Km Rodados = SUM(BaseLogistica[Km])
- Km Média = AVERAGE(BaseLogistica[Km])
- Qtd Viagens = COUNTROWS(BaseLogistica) // Quantidade de Viagens Feitas
- Cidades Atendidas = DISTINCTCOUNT(BaseLogistica[Cidade])
- Entregas no Prazo = CALCULATE(   COUNTROWS(BaseLogistica),   BaseLogistica[Status Entrega] = "No Prazo") //  
- % No Prazo = [Entregas no Prazo]/[Qtd Viagens] // % de Entregas no Prazo ou Atrasadas



## Análise e Resultados com Capturas de Tela do Dashboard

A seguir, são apresentadas algumas capturas de tela do dashboard desenvolvido, oferecendo uma visão geral das principais visualizações e insights disponibilizados.

### Pagina Inicial

![TELA-1](https://i.ibb.co/HK4T4rR/TELA-1.png)



### Viagens Realizadas

- **Quantidade de Viagens:** Detalhes sobre a quantidade total de viagens realizadas, KM Rodados.
- **Eficiência das Viagens:** Avaliação da pontualidade das entregas (dentro do prazo e atrasadas) e situações das entregas.
- **Tendências Temporais:** Distribuição da quantidade de viagens ao longo dos anos .

![TELA-2](https://i.ibb.co/f8D42kx/TELA-2.png)

### Motoristas

- **Atendimento Geográfico:** Detalhes sobre as cidades atendidas pelas viagens, 

- **Tipos de Veículos:** Dados sobre o tipo de veículo utilizado em cada viagem.

- **Avaliação de Performance:** Avaliação do desempenho dos motoristas, categorizado por região.

- **Desempenho Individual:** Análise da receita, lucro, quantidade de viagens e desempenho geral por motorista.

  ![TELA-3](https://i.ibb.co/XYJ8CYm/TELA-3.png)

### **Faturamento**

- **Receita e Lucro:** Detalhes sobre a receita total gerada, lucro obtido e análise de faturamento por veículo e marca.
- **Variação Temporal:** Análise dos valores de frete ao longo do tempo e lucratividade por estado

![TELA-4](https://i.ibb.co/LgRzT1Z/TELA-4.png)

Clique aqui e veja o Dashboard na integra : [Link do Dashboard na integra](https://app.powerbi.com/view?r=eyJrIjoiY2IzNzYyOTEtOTIxMi00MmZlLTg5YmEtNThjZjI2MWViNGE2IiwidCI6IjQ2ZDM2MzY1LTNhMGEtNDE3Ny04YTk3LThjMTUxYTY2YTlhMSJ9)



## Créditos

- O desafio, bem como muitos detalhes de sua resolução, se devem ao Alon Pinheiro, do canal do Youtube Hastag Treinamento - [Curso Básico de Power BI 2024](https://www.youtube.com/playlist?list=PLxjKFMYkZ9Ocwz4qywOc5qYLi6apNZlCw).
- Tutorial por Escrito fornecido pelo Alon Pinheiro - [Clique Aqui:](https://www.hashtagtreinamentos.com/curso-basico-de-power-bi-2024-power-bi)
- Ícones retirados do [Site Flaticon](https://www.flaticon.com/br/) : Paleta de Cor Azul -  Codigo #251670 