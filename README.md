Metodologia
Análises e Resultados
Conclusões e Insights
Próximos Passos
Referências e Anexos

<h2 align="center">Análise de vendas do DataSet Olist</h2>
<h3 align="center">Olist é uma startup brasileira que atua no segmento de tecnologia para varejo. A empresa possui soluções que facilitam a gestão de lojas off-line e online e também uma solução de aceleração de vendas dentro de marketplaces.</h3>
<img src="https://github.com/grazysmelo/Analise-de-vendas/blob/main/capa%20do%20relat%C3%B3rio.jpg" align="center">

<p>A partir desses dados, tenho como objetivo descobrir semelhanças e preferências entre os clientes, padrões de compras, sazonalidade das vendas e receitas geradas por categoria dos produtos.</p>

- #### Perguntas à serem respondidas: ####
    - [ ] Qual é a distribuição do número de pedidos e qual é o valor médio dos pedidos por estado? 
    - [ ] Qual é a distribuição dos clientes por região?
    - [ ] Como as vendas se distribuem entre diferentes categorias de produtos? Quais categorias têm melhor desempenho em termos de receita e volume?
    - [ ] Qual é o valor médio das compras (valor médio do pedido)?
    - [ ] Qual o volume de vendas para cada mês?

### Para realizar a análise, foram utilizados os seguintes passos metodológicos:
- Exploração Inicial dos Dados: Compreensão geral e verificação da qualidade dos dados.
- Análise Exploratória: Utilização de técnicas estatísticas e visualização de dados para entender melhor as características das variáveis.
- Uso de Bibliotecas: Python foi a linguagem utilizada, com bibliotecas como Pandas, Matplotlib, Seaborn e Folium.
- Visualização Geográfica: Mapas foram criados usando a biblioteca Folium para entender a distribuição geográfica das vendas.











<img src=""> print dos primeiros passos

Com uma lista de N questões a serem respondidas, inciei as análises para extrair respostas e insights que possa melhorar as vendas.
> Durante todo o processo, apareceu diversas situações que precisaram ser contornada e ajustadas de acordo com a necessidade da analise.//continua

1. Qual é a distribuição do número de pedidos e qual é o valor médio dos pedidos por estado? 
O valor médio dos pedidos por estado é de 3.683k, considerando somente 23 estados de vendas. 
São Paulo tem o maior número de pedidos, atigindo um total demais de 40.000 pedidos.

2. Qual é a distribuição dos clientes por região?
Com a ajuda do mapa de calor, conseguimos distinguir regiôes com mais clientes.

3. Como as vendas se distribuem entre diferentes categorias de produtos? Quais categorias têm melhor desempenho em termos de receita e volume?
Em relação ao nosso top 10 quantidade de pedidos, temos uma enorme diferença no volume de cada categoria. Cama, mesa e banho é a categoria 
com o maior volume, se destacando em relação as outras, com um total de 11.115k de vendas.
Em termos de receita beleza e saúde é a maior categoria, com um total de R$ 1.258.681,00 gerados nesse período.

4. Qual é o valor médio das compras (valor médio do pedido)?
O valor médio do pedido é:  161.0

5. Qual o volume de vendas para cada mês?
Representamos o volume de vedas para cada mês em um gráfico de barras.

 
Os dados foram extraidos de: https://www.kaggle.com
