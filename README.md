# 🛳️ Titanic - Machine Learning from Disaster

Este projeto faz parte do desafio do Kaggle **[Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)**, que propõe prever a sobrevivência de passageiros com base em dados como classe, idade, sexo, número de familiares a bordo, entre outros.

---

## 🎯 Objetivo

Utilizar modelos de aprendizado de máquina para prever quem sobreviveu ao naufrágio do Titanic com base em variáveis do conjunto de dados fornecido.

---

## 🧠 Modelo Utilizado

Foi utilizada uma **árvore de decisão com profundidade igual a 1**, o que significa que o modelo toma a decisão com base em apenas uma divisão (split) nos dados.

### 📌 Motivo da Escolha
A ideia era explorar a simplicidade do modelo e observar até que ponto uma decisão baseada em **apenas uma variável** poderia prever corretamente os dados de treino.

---

## ✅ Resultados

- O modelo obteve **100% de acurácia no conjunto de treino**.
- Como era esperado, por se tratar de um modelo extremamente simples, a **generalização em dados fora do treino pode ser fraca**, mas isso reforça o estudo de **overfitting** e a importância da **validação cruzada**.

---

## 🗂️ Estrutura do Projeto

- titanic_decision_tree.ipynb # Notebook com o treinamento do modelo
- train.csv # Dados de treino
- test.csv # Dados de teste
- gender_submission.csv # Resultados esperados do Kaggle
- README.md # Este arquivo

---

## ⚙️ Tecnologias e Bibliotecas

- Python 3
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (para análise exploratória)

---

## 📚 Lições Aprendidas

- Modelos simples como árvores rasas podem se ajustar perfeitamente ao treino, mas isso não garante boa performance em produção.
- A variável mais discriminativa foi suficiente para separar as classes nos dados de treino, mas isso tende a mudar com dados reais ou mais complexos.

---

## ✨ Próximos Passos

- Aplicar validação cruzada para evitar overfitting.
- Testar outros modelos mais robustos como Random Forest ou XGBoost.
- Realizar engenharia de atributos para melhorar a performance nos dados de teste.

---

> 🚢 "Not all those who wander are lost – unless they are aboard the Titanic."
