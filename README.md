# Machine_Learning_Trials

### _English_

## 1. Objective

Expertise in training and fine-tuning Machine Learning algorithms by Data Scientists is the main reason why excellent results are delivered to the company and clients.

In this context, the objective of this project was to conduct trials with Machine Learning algorithms (Classification, Regression, and Clustering) to study performance behavior as the main parameters controlling overfitting and underfitting change, considering Holdout techniques. It's worth noting that for this study, preprocessed datasets were used, separated into training, validation, and test sets, which were directly applied to the algorithms.

## 2. Solution Planning
### 2.1 Final Result

The trial resulted in 7 tables, built based on algorithm performance data, considering 3 different datasets: Training, Validation, and Test, and different parameters. These algorithms were evaluated using multiple metrics.

### 2.2 Algorithms Tested

### Classification:

-	**Algorithms:** KNN, Decision Tree, Random Forest, and Logistic Regression
- **Performance Metrics:** Accuracy, Precision, Recall, and F1-Score

### Regression:

-	**Algorithms:** Linear Regression, Decision Tree Regressor, Random Forest Regressor, Polynomial Regression, Linear Regression Lasso, Linear Regression Ridge, Linear Regression Elastic Net, Polynomial Regression Lasso, Polynomial Regression Ridge, and Polynomial Regression Elastic Net
- **Performance Metrics:**  R2, MSE, RMSE, MAE, and MAPE

### Clustering:

-	**Algorithms:** K-Means and Affinity Propagation
- **Performance Metrics:**  Silhouette Score

### 2.3 Tools Used
Python 3.8 and Scikit-learn

## 3. Development
### 3.1 Solution Strategy

For training each algorithm, the codes were written using Python, varying the main adjustment parameters and their influence on different performance metrics, considering the different datasets. The set of values that resulted in the best performances was selected for the final training of each model.

## 3.2 Step-by-step

1. Training algorithms with training data using "default" parameters;
2. Calculating algorithm performance trained with training data and "default" parameters;
3. Calculating algorithm performance trained with validation data and "default" parameters;
4. Varying the values of the main adjustment parameters of each algorithm, evaluating the set of parameters that presented the best performance;
5. Combining training and validation data;
6. Retraining each algorithm considering the union of training and validation data and the best parameters selected in the previous step;
7. Calculating the final performance of the algorithms trained considering the union of training and validation data and the best parameters;

## 5. Top Insights

1. Classification algorithms showed better performance compared to regression algorithms, which may indicate a need for better selection of attributes and preparation of independent variables in the dataset.
2. Clustering algorithms showed very low performance, which may indicate a dataset that is very dispersed and/or has low cohesion.

## 6. Results
The obtained results can be observed in the following tables:

### 6.1 Classification Trial:

- #### On training data:
  
<img width="489" alt="Screenshot 2024-07-08 at 15 00 57" src="https://github.com/jessicanadalete/machine_learning_trials/assets/99223015/e54c81aa-597c-4de0-a25e-f35728fdd616">

- #### On validation data:
  
<img width="490" alt="Screenshot 2024-07-08 at 15 07 02" src="https://github.com/jessicanadalete/machine_learning_trials/assets/99223015/894ce2ed-b6a3-48e2-96d4-2df381e7d119">

- #### On test data:
  
<img width="488" alt="Screenshot 2024-07-08 at 15 07 49" src="https://github.com/jessicanadalete/machine_learning_trials/assets/99223015/0d3b15d4-5763-4e44-a8cb-49f0bd699e3b">

### 6.2 Regression Trial:

- #### On training data:
  
<img width="541" alt="Screenshot 2024-07-08 at 15 08 28" src="https://github.com/jessicanadalete/machine_learning_trials/assets/99223015/2193a4bd-4673-484b-8873-d564e363a72b">

- #### On validation data:
  
<img width="540" alt="Screenshot 2024-07-08 at 15 09 00" src="https://github.com/jessicanadalete/machine_learning_trials/assets/99223015/afa9edbe-b91c-467a-9e7a-c5a016c3e805">

- #### On test data:
  
<img width="535" alt="Screenshot 2024-07-08 at 15 09 26" src="https://github.com/jessicanadalete/machine_learning_trials/assets/99223015/7031bd8a-b4d7-4a68-bd36-603a9c04fa48">

### 6.3 Clustering Trial:
<img width="402" alt="Screenshot 2024-07-08 at 15 10 05" src="https://github.com/jessicanadalete/machine_learning_trials/assets/99223015/6265fdd5-b55e-43ef-8741-ddeb93542098">

## 7. Conclusions
In this Machine Learning trial, I was able to generate new knowledge and experience with different models, allowing me to better understand the performance behavior of these models regarding the variation of their main adjustment and control parameters between the states of underfitting and overfitting.

## 8. Next Steps
As the next steps of this trial, I plan to experiment another different Machine Learning algorithms and use different datasets to increase knowledge about the algorithms, willing to understand the conditions and parameters most favorable for improving the performance of each model.


___________________________________________________
### Português

## 1. Objetivo

A expertise no treinamento e no ajuste fino de algoritmos de Machine Learning, feito por Cientistas de Dados, é o principal motivo pelo qual são entregues ótimos resultados à empresa e aos clientes.

Neste contexto, o objetivo desse projeto foi realizar ensaios com algoritmos de Machine Learning (Classificação, Regressão e Clusterização), para estudar o comportamento da performance, conforme a mudança dos principais parâmetros de controle de _overfitting_ e _underfitting_, considerando técnicas de _Holdout_. 
Cabe destacar que para este estudo, foram utilizados conjunto de dados previamente tratados e separados em treino, validação e teste, os quais foram diretamente aplicados nos algoritmos.

## 2. Planejamento da solução

### 2.1 Resultado Final
  
O ensaio resultou em 7 tabelas, construídas com base em dados de performance dos algoritmos, considerando 3 conjuntos de dados diferentes: Treinamento, Validação e Teste e diferentes parâmetros, sendo estes algoritmos avaliados utilizando múltiplas métricas.

### 2.2 Algoritmos ensaiados

#### Classificação:

- **Algoritmos:** KNN, Decision Tree, Random Forest e Logistic Regression
- **Métricas de performance:** Accuracy, Precision, Recall e F1-Score

#### Regressão:

- **Algoritmos:** Linear Regression, Decision Tree Regressor, Random Forest Regressor, Polinomial Regression, Linear Regression Lasso, Linear Regression Ridge, Linear Regression Elastic Net, Polinomial Regression Lasso, Polinomial Regression Ridge e Polinomial Regression Elastic Net
- **Métricas de performance:** R2, MSE, RMSE, MAE e MAPE

#### Agrupamento:
- **Algoritmos:** K-Means e Affinity Propagation
- **Métricas de performance:** Silhouette Score

### 2.3 Ferramentas utilizadas:

Python 3.8 e Scikit-learn

## 3. Desenvolvimento

### 3.1 Estratégia da solução

Para treinamento de cada algoritmo, os códigos foram escritos utilizando a linguagem Python, variando-se os principais
parâmetros de ajuste e sua influência sobre diferentes métricas de performance, considerando os diferentes conjuntos de dados.
O conjunto de valores que culminaram em melhores performances, foram selecionados para o treinamento final de cada modelo.

### 3.2 O passo a passo

1. Treinamento dos algoritmos com os dados de treinamento, utilizando os parâmetros “padrão”;
2. Cálculo da performance dos algoritmos treinados com o conjunto de dados de treinamento e com os parâmetros “padrão”;
3. Cálculo da performance dos algoritmos treinados com o conjunto de dados de validação e com os parâmetros “padrão”;
4. Variação dos valores dos principais parâmetros de ajuste de cada algoritmo, avaliando-se o conjunto de parâmetros apresente a melhor performance;
5. União dos dados de treinamento e validação
6. Retreino de cada algoritmo considerando a união dos dados de treinamento e validação, e os melhores parâmetros selecionados em etapa anterior;
7. Cálculo da performance final dos algoritmos treinados considerando a união dos dados de treinamento e validação, e os melhores parâmetros;

## 5. _Top insights_

1. Os algoritmos de Classificação apresentaram melhor performance quando comparados aos algoritmos de Regressão, o que pode demonstrar uma necessidade de melhor seleção de atributos e preparação das variáveis independentes do conjunto de dados.
   
2. Os algortirmos de agrupamento apresentaram performance bem baixa, o que pode demonstrar um conjunto de dados muito disperso e/ou baixa coesão.
   
## 6. Resultados

Os resultados obtidos podem ser observados nas tabelas a seguir:

### 6.1 Ensaio de Classificação:

- #### Sobre os dados de treinamento:

<img width="489" alt="Screenshot 2024-07-08 at 15 00 57" src="https://github.com/jessicanadalete/machine_learning_trials/assets/99223015/e54c81aa-597c-4de0-a25e-f35728fdd616">

- #### Sobre os dados de validação:

<img width="490" alt="Screenshot 2024-07-08 at 15 07 02" src="https://github.com/jessicanadalete/machine_learning_trials/assets/99223015/894ce2ed-b6a3-48e2-96d4-2df381e7d119">

- #### Sobre os dados de teste:

<img width="488" alt="Screenshot 2024-07-08 at 15 07 49" src="https://github.com/jessicanadalete/machine_learning_trials/assets/99223015/0d3b15d4-5763-4e44-a8cb-49f0bd699e3b">

### 6.2 Ensaio de Regressão:

- #### Sobre os dados de treinamento:

<img width="541" alt="Screenshot 2024-07-08 at 15 08 28" src="https://github.com/jessicanadalete/machine_learning_trials/assets/99223015/2193a4bd-4673-484b-8873-d564e363a72b">

- #### Sobre os dados de validação:

<img width="540" alt="Screenshot 2024-07-08 at 15 09 00" src="https://github.com/jessicanadalete/machine_learning_trials/assets/99223015/afa9edbe-b91c-467a-9e7a-c5a016c3e805">

- #### Sobre os dados de teste:

<img width="535" alt="Screenshot 2024-07-08 at 15 09 26" src="https://github.com/jessicanadalete/machine_learning_trials/assets/99223015/7031bd8a-b4d7-4a68-bd36-603a9c04fa48">

### 6.3 Ensaio de Agrupamento:

<img width="402" alt="Screenshot 2024-07-08 at 15 10 05" src="https://github.com/jessicanadalete/machine_learning_trials/assets/99223015/6265fdd5-b55e-43ef-8741-ddeb93542098">

## 7. Conclusões

Nesse ensaio de Machine Learning, consegui gerar novos conhecimentos e experiência acerca de diferentes modelos, me permitindo entender melhor sobre o comportamento da performance destes modelos em relação à variação de seus principais parâmetros de ajuste e de controle entre os estados de _underfitting_ e _overfitting_.

## 8. Próximos passos
Como próximos passos desse ensaio, pretendo ensaiar novos algoritmos de Machine Learning e usar diferentes conjuntos de dados para aumentar o conhecimento sobre os algoritmos, de forma a entender as condições e os parâmetros mais favoráveis ao aumento da performance de cada modelo.
