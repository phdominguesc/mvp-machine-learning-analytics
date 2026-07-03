# MVP — Machine Learning & Analytics

Este repositório contém o MVP da sprint de Machine Learning & Analytics da pós-graduação em Data Science.

## Autor

Pedro Curvello

## Objetivo do projeto

O objetivo deste MVP é desenvolver e comparar modelos de Machine Learning para prever o resultado final de partidas da Premier League 2023/2024.

O problema foi tratado como uma classificação multiclasse, com três possíveis resultados:

- vitória do time mandante;
- empate;
- vitória do time visitante.

## Dataset

O dataset utilizado contém partidas da Premier League 2023/2024.

A fonte original dos dados é o site football-data.co.uk.

Para atender aos requisitos da entrega, o arquivo CSV também foi disponibilizado neste repositório e é carregado no notebook por meio de uma URL pública do GitHub.

## Arquivos do repositório

- `MVP_—_Machine_Learning_&_Analytics_(Pedro_Curvello).ipynb`: notebook principal do MVP.
- `premier_league_2023_2024.csv`: dataset utilizado no projeto.

## Técnicas utilizadas

- Análise exploratória de dados
- Pré-processamento com pipelines
- OneHotEncoder
- StandardScaler
- DummyClassifier como baseline
- Regressão Logística
- Random Forest
- GridSearchCV
- Avaliação com acurácia, F1-score macro, matriz de confusão e relatório de classificação

## Resultado final

O melhor modelo foi a Regressão Logística otimizada, que apresentou o melhor F1-score macro no conjunto de teste.

O modelo superou o baseline e mostrou capacidade de capturar padrões nos dados, embora ainda tenha limitações, principalmente na previsão de empates.

## Observação

Este projeto tem finalidade acadêmica. Apesar de utilizar odds pré-jogo como variáveis explicativas, o trabalho não tem o objetivo de incentivar apostas esportivas.
