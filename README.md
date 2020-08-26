#  Abordagem teórica sobre a estratificação de municípios para análise  situacional em relação ao COVID-19.

 

 1. Como comparar municípios? (descritiva)
Imagine que um gestor público entra hoje no Farol e quer ter a possibilidade de comparar seu município com outros municípios de seu interesse.  **(a)Como você selecionaria municípios para comparação?Descreva quais caracaterísticas você selecionaria para definir municípios semelhantes. (b) Descreva 2 (duas) análises ou visualizações que você montaria para comparar a situação entre esses municípios.**

	O desenvolvimento desse tipo de análise é de extrema importância para que possamos comparar a real situação do município em relação à outros. Há duas abordagens que podemos utilizar para selecionar os municípios para uma comparação em relação ao avanço do COVID-19.
    

 - **Abordagem 1** : Numa mesma fonte de dados, como os fornecidos pelo [Farol Covid](https://farolcovid.coronacidades.org/) selecionamos dois municípios quaisquer e comparamos algumas variáveis como o números de mortes, contaminados e recuperados do COVID-19 em um determinado intervalo de tempo.  Essa abordagem é pouco efetiva pois desconsidera fatores relevantes que podem ajudar a entender melhor sobre o comportamento do vírus já que provavelmente estaremos comparando municípios com realidades totalmente diferentes.
 
 - **Abordagem 2** :  Selecionando uma fonte de dados confiável, como o [Farol Covid](https://farolcovid.coronacidades.org/) ou o [Painel Coronavírus](https://covid.saude.gov.br/) podemos então desenvolver um algoritmo para selecionar municípios semelhantes e então comparar os números fornecidos pelos *datasets*. 
	  A estratificação dos municípios seria feita a partir de diferentes indicadores demográficos, socio-econômicos, condições de saúde e estrutura de serviços que podem ser encontrados no site do [IBGE](https://www.ibge.gov.br/). Alguns dos indicadores mais importantes para essa comparação são:

**Demográficos:**

   - população
    
   - densidade demográfica
    
   - percentual de domicílios urbanos
    
**Socioeconômicos:**

  - PIB  _per capita_
    
   - índice de Gini
    
   - cobertura de plano de saúde
    
  - percentual de extrema pobreza
    
  - taxa de desemprego da população com 18 anos ou mais de idade

**Condições de saúde:**
  - esperança de vida ao nascer
    
   - taxa de mortalidade de menores de 5 anos de idade
    
   - taxa de envelhecimento

**Estrutura de serviços:**
   - cobertura da Saúde da Família
    
   - taxa de procedimentos de média complexidade
    
   - razão de internações clínico-cirúrgicas de média complexidade
   
	 Como buscamos comparar a realidade de saúde entre diferentes municípios, poderíamos utilizar esses indicadores que foram anteriormente correlacionados através do estudo feito no artigo [Estratificação de municípios brasileiros para avaliação de desempenho em saúde](https://www.scielo.br/scielo.php?pid=S2237-96222016000400767&script=sci_arttext) e quem sabe fazer uma nova correlação, envolvendo então as *features* descritas com o número de contaminados pelo  COVID por exemplo.
