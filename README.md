# child-mortality-brazil-kaggle

Predição da probabilidade de óbito de um bebê a partir de dados da mãe, do pré-natal e do parto.

Os conjuntos de dados utiizados neste trabalho são referentes a óbitos de crianças no Brasil e estão disponíveis na plataforma Kaggle.

Foram avaliados cinco modelos de classificação disponíveis na biblioteca Scikit-Learn: 
1) Regressão Logística (Logistic Regression)
2) Árvores de Decisão (Decision Trees)
3) K-Vizinhos Próximos (K-Nearest Neighbors)
4) Gaussian Naive Bayes
5) Máquinas de Vetores de Suporte (Support Vector Machines)

Os modelos acima foram associados a três diferentes técnicas de subamostragem:
1) Random Undersampler
2) NearMiss
3) One Sided Selection

*O modelo baseado em Naive Bayes obteve melhor desempenho médio em treino com a estratégia de validação cruzada K-Fold, associado à tecnica Random Undersampling. Após o ajuste de hiperparâmetros, ***a acurácia do modelo foi de 91%*** no conjunto de teste.*

---

Prediction of the probability of a baby's death based on mother, prenatal and delivery data.

Five classification models available in the Scikit-Learn library were evaluated:
1) Logistic Regression
2) Decision Trees
3) K-Nearest Neighbors
4) Gaussian Naive Bayes
5) Support Vector Machines

The models above were associated with three different undersampling techniques:
1) Random Undersampler
2) NearMiss
3) One Sided Selection

*The model based on Naive Bayes obtained the best average performance in training with the K-Fold cross validation strategy, associated with the Random Undersampling technique. After adjusting the hyperparameters, ***the model accuracy was 91%*** in the test set.*

---

Projeto desenvolvido para o segundo módulo do curso de Especialização em Inteligência Artifical Aplicada, semestre 2021/2, do Instituto Federal de Goiás - Câmpus Goiânia.
