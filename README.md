<h2 align="center">Análise de vendas do DataSet Olist</h2>
<h3 align="center">Olist é uma startup brasileira que atua no segmento de tecnologia para varejo. A empresa possui soluções que facilitam a gestão de lojas offline e online e também uma solução de aceleração de vendas dentro de marketplaces.</h3>
<img src="https://github.com/grazysmelo/Analise-de-vendas/blob/main/imagens/capa%20do%20relat%C3%B3rio.jpg" align="center">

<p>A partir desses dados, tenho como objetivo descobrir semelhanças e preferências entre os clientes, padrões de compras, sazonalidade das vendas e receitas geradas por categoria dos produtos.  <br> Foi selecionado um conjunto de dados disponibilizado pela Olist, a maior loja de departamento dos "marketplaces", com informações de mais de 100 mil pedidos de 2016 a 2018.</p>

- #### Perguntas a serem respondidas: ####
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


- #### Análise 1 ####
    - [x] Qual é a distribuição do número de pedidos e qual é o valor médio dos pedidos por estado?

<p>A análise revelou que há uma predominância de pedidos no Sudeste do Brasil. O valor médio dos pedidos por estado é de: R$3.683.</p>
<p>Com a maior concentração de clientes no estado de São Paulo, foram realizados um total de mais de 40.000 pedidos.</p>
<img src="https://github.com/grazysmelo/Analise-de-vendas/blob/main/imagens/quantidade%20de%20pedidos%20por%20estado.png" align="center">


- #### Análise 2 ####
    - [x] Qual é a distribuição dos clientes por região?

<img src="https://github.com/grazysmelo/Analise-de-vendas/blob/main/imagens/heatmap.png" align="center">
<p>Alguns resultados gerados a partir do mapa de calor foram: </p>
<p>1. A maior concentração de clientes está localizada na região Sudeste.</p>
<p>2. As regiões Sul e Nordeste também apresentam concentrações significativas de clientes, especialmente em estados como Rio Grande do Sul e Bahia.</p>
<p>3. As regiões Norte e Centro-Oeste mostram menor densidade de clientes. Isso pode indicar a necessidade de estratégias específicas para aumentar a penetração nessas regiões.</p>
<p>Compreender a distribuição geográfica dos clientes é crucial para a segmentação de mercado e para a definição de estratégias de marketing.</p>


- #### Análise 3 ####
    - [x] Como as vendas se distribuem entre diferentes categorias de produtos? Quais categorias têm melhor desempenho em termos de receita e volume?

<p>Em relação ao nosso top 10 quantidade de pedidos, temos uma enorme diferença no volume de cada categoria. Cama, mesa e banho é a categoria 
com o maior volume, destacando-se em relação às outras, com um total de 11.115k de vendas.</p>
<img src="https://github.com/grazysmelo/Analise-de-vendas/blob/main/imagens/tabela%20volume%20por%20categoria.png" align="center">
<p>Em termos de receita, Beleza e Saúde é a maior categoria, com um total de R$ 1.258.681,00 gerados nesse período.</p>

- #### Análise 4 ####
    - [x] Qual é o volume de vendas para cada mês?

<img src="https://github.com/grazysmelo/Analise-de-vendas/blob/main/imagens/volume%20de%20vendas%20por%20m%C3%AAs.png" align="center">
<p>Pode-se observar um crescimento constante nas vendas ao longo do período analisado, com exceção de pequenas flutuações em alguns meses. Isso indica um aumento na demanda dos produtos ou uma expansão de clientes.</p>
<p>Entender o volume de vendas por mês é crucial para gerenciar estoques de maneira eficaz.</p>

> 🐛 Dificuldades:
> A integração entre diferentes bibliotecas de Python, como `Pandas` e `Folium`, apresentou desafios iniciais, especialmente na configuração dos parâmetros para a visualização correta dos mapas. Esses desafios proporcionaram um aprendizado valioso, especialmente na área de análise dos dados e na escolha das ferramentas adequadas para visualização. As soluções encontradas não só ajudaram a completar o projeto, mas também contribuíram para o desenvolvimento de habilidades que serão úteis em projetos futuros.

### Conclusões:
- A análise mostrou que o volume de vendas está diretamente ligado às sazonalidades, com a maioria dos clientes localizados em grandes centros urbanos, como São Paulo e Rio de Janeiro. Os produtos de cama, mesa e banho são os mais vendidos, mas a categoria de Beleza e Saúde é a mais lucrativa. 

### Principais Insights:
- Foco em promoções nos meses de pico pode aumentar ainda mais as vendas.
- Implementar campanhas de marketing específicas para o período de maior demanda.
- Explorar novos mercados geográficos, especialmente em regiões menos atendidas.

<a href="https://www.kaggle.com/code/leandroal/an-lise-do-e-commerce-no-brasil-olist-dataset/input">Os dados foram extraídos de: kaggle.com</a>
<p> </p>
<a href="https://github.com/grazysmelo/Analise-de-vendas/blob/main/An%C3%A1lise%20do%20e-commerce%20no%20Brasil.ipynb">Jupyter Notebook</a>
