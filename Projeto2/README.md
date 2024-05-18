
## Projeto: pinguins_analysis.py

### Sobre o Projeto

Este projeto contém o código com o propósito de análise de dados de pinguins realizado por uma ONG.


### Descrição do Problema

A ONG resgata pinguins que são levados pelas correntes marítimas para as praias do sul do país. No entanto, nem todos os pinguins possuem suas informações devidamente registradas, dificultando a análise da origem de cada um.


### Objetivo

O objetivo deste projeto é desenvolver modelos de machine learning para prever a espécie de um pinguim com base em suas características físicas, como tamanho do bico, comprimento da nadadeira e massa corporal. Essa previsão permitirá a ONG:

* **Melhorar a análise de dados:** com a espécie do pinguim conhecida, a ONG pode analisar melhor os dados coletados, como a origem dos pinguins e o impacto da atividade humana.


### Modelos Desenvolvidos

O projeto utiliza dois modelos de machine learning para classificação:

* **Random Forest:** um modelo de ensemble que combina múltiplas árvores de decisão para fazer previsões.
* **K-Nearest Neighbors (KNN):** um modelo de classificação baseado na distância entre os dados de teste e os dados de treinamento.


### Resultados Obtidos

Os modelos foram treinados e avaliados utilizando o conjunto de dados de pinguins. Os resultados foram promissores, com ambos os modelos atingindo alta precisão. 

* O modelo **Random Forest** obteve uma precisão de **98.8%** na validação cruzada.
* O modelo **KNN** obteve uma precisão de **100%** na validação cruzada.

### Ferramentas Utilizadas

Os projetos são desenvolvidos utilizando Python, juntamente com bibliotecas como Pandas, Matplotlib e Scikit-Learn para análise e modelagem de dados.

