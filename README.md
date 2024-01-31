# Prevendo o retorno em vendas de investimentos em marketing

## Objetivo
Analisar uma base de dados de um cliente fictício que contem dados sobre o investimento em marketing através das plataformas Youtube, Facebook e jornais; e o valor gerado das vendas. Para a parte de análise, faremos uma análise descritiva e exploratória dos dados, com o objetivo de entender melhor as variáveis, encontrar possíveis problemas com os dados, correlacionar as variáveis e identificar desvios e outliers.

Além disso, o cliente deseja um modelo simples de regressão para fazer previsões do retorno de vendas a partir de uma determinada combinação de investimento em publicidade nas plataformas utilizadas.

## Esclarecimento

Devido a ausência de maiores informações descritivas sobre a base de dados, interpretarei os valores na moeda unidade monetária (abreviado como: UM)

## Metodologia

Bibliotecas:

Pandas e Seaborn para análise descritiva dos dados
Scikit Learn para modelação

## Resultados

Após a construção de um modelo preditivo utilizando uma regressão linear, fiz um teste e plotei em um gráfico para ver o quão bem os valores da predição se assemelhavam aos valores reais e cheguei ao seguinte resultado:
![image](https://github.com/yfaleiro/Prevendo-vendas-por-investimento-em-MKT/assets/116303455/3c36afea-16f8-4b0d-a347-5e925dbe40a3)

Após alguns testes, foi possível identificar que o investimento em jornais tem um efeito irrisório no valor de vendas.
