# Previsão de Preço de Casa com Regressão Linear Múltipla

## Descrição do Projeto

Este projeto tem como objetivo prever o preço de uma casa com base em múltiplas variáveis independentes, como **tamanho da casa**, **número de quartos**, e **idade da casa**. Para isso, utilizamos um modelo de Regressão Linear Múltipla, que permite estimar o preço a partir dessas três variáveis.

## Objetivos
- Criar um dataset com três variáveis independentes para análise.
- Treinar um modelo de Regressão Linear Múltipla para prever o preço das casas.
- Avaliar o desempenho do modelo utilizando o **Erro Quadrático Médio (MSE)** e o **Coeficiente de Determinação (R²)**.
- Visualizar os resultados e interpretar a relação entre as variáveis independentes e o preço previsto.

## Tecnologias Utilizadas
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Numpy

## Metodologia

1. **Geração dos Dados**: Criamos um dataset com três variáveis independentes: **tamanho da casa** (em metros quadrados), **número de quartos** e **idade da casa** (em anos). A variável dependente é o **preço**.
2. **Divisão dos Dados**: O dataset foi dividido em conjunto de treino e teste, sendo que o conjunto de treino foi utilizado para ajustar o modelo, e o conjunto de teste para validar o desempenho.
3. **Treinamento do Modelo**: Foi treinado um modelo de Regressão Linear Múltipla utilizando os dados de treino.
4. **Avaliação do Modelo**: O desempenho do modelo foi avaliado com as métricas **MSE** (Erro Quadrático Médio) e **R²** (Coeficiente de Determinação), que indicam a precisão das previsões.
5. **Visualização dos Resultados**: Como há múltiplas variáveis, os resultados foram visualizados com gráficos de dispersão e correlação, além da análise das métricas de desempenho.

## Resultados

- O modelo foi capaz de prever o preço das casas com base em várias variáveis, apresentando uma boa performance de acordo com o **MSE** e o **R²**.
- As variáveis **tamanho da casa** e **número de quartos** demonstraram maior influência no preço, enquanto a **idade da casa** apresentou uma correlação mais fraca.
- A visualização gráfica permitiu observar as tendências e padrões entre as variáveis independentes e o preço das casas.
