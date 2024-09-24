# HeartDisease

## 1. Análise de Dados

Essa é a primeira parte do nosso processo de classificação do dataset Heart Disease. A análise de dados é uma etapa crucial, pois nos permite compreender o comportamento das variáveis e suas relações com a variável-alvo, a presença ou ausência de doença cardíaca.

Realizamos uma análise unidimensional, explorando a distribuição das variáveis numéricas e categóricas, identificando possíveis outliers e padrões de comportamento. Em seguida, partimos para análises bidimensionais, observando interações entre diferentes variáveis e suas correlações, especialmente em relação ao target (doença ou não).

Além disso, focamos nas variáveis preditoras como idade, colesterol, pressão arterial, frequência cardíaca máxima, entre outras, comparando-as com o target. Essas comparações foram essenciais para identificar quais fatores parecem estar mais fortemente relacionados à presença da doença.

Para realizar essas análises, utilizamos ferramentas como Matplotlib, Seaborn e Plotly para criar diversas visualizações, incluindo subplots, boxplots e heatmaps. Esses gráficos nos ajudaram a interpretar as correlações e identificar as variáveis mais relevantes no processo de classificação.


### 1.1 Compreensão e Entendimento dos Dados:

Nosso dataset possui 14 colunas, que são:

![image](https://github.com/user-attachments/assets/d1b9ad9d-d412-426d-bf5b-5af9e4564fdf)

Baseado nisso, um dicionário de dados e um dicionário de metadados foi feito. Passos fundamentais para entedermos nossa base de dados e suas peculariades, como nulidade das colunas, cardinalidade. 

![image](https://github.com/user-attachments/assets/51d0b6b0-d8e2-4ac4-acb1-27c973ffea9d)

### 1.2 Análises Unidimensionais:
Trouxe primeiramente algumas análises unidimensionais para entendermos de fato a particularidade dessas colunas.
Foi feito uso de subplots, como nesse caso de boxplots com nossas colunas numéricas>

![image](https://github.com/user-attachments/assets/2db17d83-7980-404b-954e-3efa35950fd6)

Também categorizei algumas counas, para uma análise mais agrupada, como o caso da coluna Idade, em que agrupei em trÊs grupos. Essa foi a distribuição:

![image](https://github.com/user-attachments/assets/c1a91907-9719-44d7-95b5-db277ea50410)

Como dito acima, o plotly foi usado em alguns momentos, para entedermos a particularidade de cada uma das bibliotecas em Python:

![image](https://github.com/user-attachments/assets/4eb252e8-3ff3-42f5-b4ad-313a8954b908)

### 1.3 Análises Bidimensionais:
#### 1.3.1 Análises Não Envolvendo o Target:

Trouxe a relação da nossa coluna numérica Idade com 4 outras colunas numéricas. Para isso, utilizei o Scatterplot, além dos subplots:

![image](https://github.com/user-attachments/assets/84974f76-0109-4cd3-a18f-646045128967)

Além disso, fiz uma relação entre colunas numéricas com a coluna categórica 'Sexo', em que vimos a diferença de valores nos gêneros. Também utilizei subplots, mas nessa situação, em Plotly:

![image](https://github.com/user-attachments/assets/9573627b-d9b5-4721-b345-e048af5c40a8)

#### 1.3.2 Análises com o Target:

Esse caso foi feita uma análise entre o target e o sexo, entendeno se os gÊneros possuem alguma diferença em relação a porcentagem de enfermos. E pudemos ver que, de fato, existe. Nesse caso também fiz uma caixa de texto para representar algumas informações que geram valor ao gráfico:

![image](https://github.com/user-attachments/assets/2cae8870-373f-4436-b34e-da7a6d60bc24)

O caso abaixo foi feita uma função para relacionar algumas colunas numéricas com nosso target:

![image](https://github.com/user-attachments/assets/c2400ed9-5adb-4db7-9401-3ecaf1690399)

### 1.4 Análise Multidimensional:
![image](https://github.com/user-attachments/assets/150c0469-9081-401e-ba62-ee1ecfab9e21)







