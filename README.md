<h2 align="center">Análise de vendas do DataSet Olist</h2>
<h3 align="center">Olist é uma startup brasileira que atua no segmento de tecnologia para varejo. A empresa possui soluções que facilitam a gestão de lojas off-line e online e também uma solução de aceleração de vendas dentro de marketplaces.</h3>
<img src="https://github.com/grazysmelo/Analise-de-vendas/blob/main/imagens/capa%20do%20relat%C3%B3rio.jpg" align="center">

<p>A partir desses dados, tenho como objetivo descobrir semelhanças e preferências entre os clientes, padrões de compras, sazonalidade das vendas e receitas geradas por categoria dos produtos.</p>

- #### Perguntas à serem respondidas: ####
    - [ ] Qual é a distribuição do número de pedidos e qual é o valor médio dos pedidos por estado? 
    - [ ] Qual é a distribuição dos clientes por região?
    - [ ] Como as vendas se distribuem entre diferentes categorias de produtos? Quais categorias têm melhor desempenho em termos de receita e volume?
    - [ ] Qual o volume de vendas para cada mês?

### Para realizar a análise, foram utilizados os seguintes passos metodológicos:
- Exploração Inicial dos Dados: Compreensão geral e verificação da qualidade dos dados.
- Análise Exploratória: Utilização de técnicas estatísticas e visualização de dados para entender melhor as características das variáveis.
- Uso de Bibliotecas: Python foi a linguagem utilizada, com bibliotecas como Pandas, Matplotlib, Seaborn e Folium.
- Visualização Geográfica: Mapas foram criados usando a biblioteca Folium para entender a distribuição geográfica das vendas.
<img src="https://github.com/grazysmelo/Analise-de-vendas/blob/main/imagens/primeiros%20passos.png" align="center">


- #### Analise 1 ####
    - [x] Qual é a distribuição do número de pedidos e qual é o valor médio dos pedidos por estado?

<p>A analise revelou que há uma predominância de pedidos no sudeste do Brasil. O valor médio dos pedidos por estado é de: 3.683</p>
<p>Com a maior concentração de clientes no estado de São Paulo, foi atigindo um total de mais de 40.000 pedidos</p>
<img src="https://github.com/grazysmelo/Analise-de-vendas/blob/main/imagens/quantidade%20de%20pedidos%20por%20estado.png" align="center">


- #### Analise 2 ####
    - [x] Qual é a distribuição dos clientes por região?

<img src="https://github.com/grazysmelo/Analise-de-vendas/blob/main/imagens/heatmap.png" align="center">
<a href="http://127.0.0.1:5500/notebooks/heat_map.html" align="center">HeatMap.html</a>
<p>Alguns resultados gerados a partir do mapa de calor foram: 
    1. A maior concentração de clientes está localizada na região Sudeste.
    2. As regiões Sul e Nordeste também apresentam concentrações significativas de clientes, especialmente em estados como Rio Grande do Sul e Bahia. 
    3. As regiões Norte e Centro-Oeste mostram menor densidade de clientes. Isso pode indicar a necessidade de estratégias específicas para aumentar a penetração nessas regiões</p>
<p>Compreender a distribuição geográfica dos clientes é crucial para a segmentação de mercado e para a definição de estratégias de marketing.</p>


- #### Analise 3 ####
    - [x] Como as vendas se distribuem entre diferentes categorias de produtos? Quais categorias têm melhor desempenho em termos de receita e volume?

<p>Em relação ao nosso top 10 quantidade de pedidos, temos uma enorme diferença no volume de cada categoria. Cama, mesa e banho é a categoria 
com o maior volume, se destacando em relação as outras, com um total de 11.115k de vendas.</p>
<p>Em termos de receita beleza e saúde é a maior categoria, com um total de R$ 1.258.681,00 gerados nesse período.</p>
<img src="https://github.com/grazysmelo/Analise-de-vendas/blob/main/imagens/tabela%20volume%20por%20categoria.png" align="center">


- #### Analise 4 ####
    - [x] Qual o volume de vendas para cada mês?

<img src="https://github.com/grazysmelo/Analise-de-vendas/blob/main/imagens/volume%20de%20vendas%20por%20m%C3%AAs.png" align="center">
<p>Pode se observar um crescimento constante nas vendas ao longo do período analisado, com exceção de pequenas flutuações em alguns meses. Isso indica um aumento na demanda dos produtos ou uma expansão de clientes.</p>
<p>Entender o volume de vendas por mês é crucial para gerenciar estoques de maneira eficaz.</p>

> Um resumo sobre dificuldades

### Conclusões:
- A análise mostrou que o volume de vendas está diretamente ligadas à sazonalidades, com a maioria dos clientes localizados em grandes centros urbanos, como São Paulo e Rio de Janeiro. Os produtos de cama, mesa e banho são os mais vendidos, mas a categoria de beleza e saúde é a mais lucrativa. 

### Principais Insights:
- Foco em promoções nos meses de pico pode aumentar ainda mais as vendas.
- Implementar campanhas de marketing específicas para o período de maior demanda.
- Explorar novos mercados geográficos, especialmente em regiões menos atendidas.

 
<p>Os dados foram extraidos de: [https://www.kaggle.com](https://www.kaggle.com/code/leandroal/an-lise-do-e-commerce-no-brasil-olist-dataset/input) <br> Foi selecionado um conjunto de dados disponibilizado pela Olist, a maior loja de departmento dos "marketplaces", com informações de mais de 100 mil pedidos de 2016 a 2018.</p>
<p>[Jupyter Notebook](https://github.com/grazysmelo/Analise-de-vendas/blob/main/An%C3%A1lise%20do%20e-commerce%20no%20Brasil.ipynb)</p>
