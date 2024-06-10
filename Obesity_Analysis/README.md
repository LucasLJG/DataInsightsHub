### Sobre o Projeto

Este projeto contém o código com o propósito de análise de dados de obesidade utilizando um conjunto de dados do Kaggle.

### Descrição do Problema

O conjunto de dados do Kaggle contém informações sobre características físicas e hábitos de vida de indivíduos, que são usados para classificar diferentes tipos de peso. A correta classificação dos tipos de peso é essencial para entender melhor os fatores que contribuem para a obesidade e ajudar na criação de políticas públicas e estratégias de intervenção.

### Objetivo

O objetivo deste projeto é desenvolver modelos de machine learning para prever a categoria de peso de um indivíduo com base em suas características físicas e hábitos de vida. As categorias de peso incluem: `Normal_Weight`, `Overweight_Level_I`, `Overweight_Level_II`, `Obesity_Type_I`, `Insufficient_Weight`, `Obesity_Type_II`, e `Obesity_Type_III`. Essa previsão permitirá ao pesquisador:

- **Analisar melhor os dados**: Com a categoria de peso conhecida, o pesquisador pode analisar melhor os dados coletados, como a distribuição de peso na população e os fatores associados a cada categoria.
- **Identificar tendências**: O pesquisador poderá identificar padrões nos dados que auxiliam na tomada de decisões sobre intervenções e políticas de saúde pública.

### Modelos Desenvolvidos

O projeto utiliza diversos modelos de machine learning para classificação:

- **Random Forest**: Um modelo de ensemble que combina múltiplas árvores de decisão para fazer previsões.
- **Gradient Boosting**: Um modelo de ensemble que constrói árvores de decisão sequencialmente para reduzir erros.
- **SVC (Support Vector Classifier)**: Um modelo que encontra um hiperplano para separar as classes.
- **Logistic Regression**: Um modelo linear para classificação que usa a função logística.
- **K-Nearest Neighbors (KNN)**: Um modelo de classificação baseado na distância entre os dados de teste e os dados de treinamento.
- **Gaussian Naive Bayes**: Um modelo probabilístico simples baseado no teorema de Bayes.
- **MLPClassifier (Multi-layer Perceptron)**: Um modelo de rede neural artificial.
- **Voting Classifier**: Um modelo de ensemble que combina as previsões de múltiplos modelos base.

### Resultados Obtidos

Os modelos foram treinados e avaliados utilizando o conjunto de dados de obesidade do Kaggle. Os resultados foram promissores, com vários modelos atingindo alta precisão. A validação cruzada foi utilizada para avaliar a capacidade de generalização dos modelos:

- **Random Forest**: Obteve uma precisão média de validação cruzada de 96.6%.
- **Gradient Boosting**: Obteve uma precisão média de validação cruzada de 97.7%.
- **SVC**: Obteve uma precisão média de validação cruzada de 80.2%.
- **Logistic Regression**: Obteve uma precisão média de validação cruzada de 76.1%.
- **K-Nearest Neighbors**: Obteve uma precisão média de validação cruzada de 75.1%.
- **Gaussian Naive Bayes**: Obteve uma precisão média de validação cruzada de 67.8%.
- **MLPClassifier**: Obteve uma precisão média de validação cruzada de 92.5%.
- **Voting Classifier**: Obteve uma precisão média de validação cruzada de 95.2%.

### Ferramentas Utilizadas

O projeto foi desenvolvido utilizando Python, juntamente com bibliotecas como Pandas, Matplotlib, Seaborn, Scikit-Learn, e NumPy para análise e modelagem de dados.
