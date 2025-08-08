# 🛒 Predição de Receita de Vendas com Machine Learning

Este projeto utiliza algoritmos de machine learning para prever a receita de vendas com base em dados transacionais (quantidade e preço unitário). O foco foi garantir precisão e estabilidade, especialmente após remoção de outliers.

## 📌 Objetivo
Prever a receita total (faturamento) por item vendido utilizando regressão com o algoritmo Random Forest.

---

## 🧠 Tecnologias utilizadas
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🔍 Etapas realizadas

1. **Carregamento de dados do Kaggle**
2. **Criação da variável target (`Revenue`)**
3. **Remoção de outliers** com base em valores extremos de receita
4. **Modelagem com Random Forest**
5. **Otimização com GridSearchCV**
6. **Validação cruzada (5 folds)**
7. **Avaliação com RMSE e análise de importância das variáveis**
8. **Visualização de gráficos de predição e resíduos**

---

## 📊 Resultados

- **RMSE médio (5 folds)**: `0.0612`
- **Desvio padrão**: `0.0147`
- **Melhores parâmetros**: `n_estimators=200, max_depth=None, min_samples_split=2`
- **Importância das variáveis**:
  - Quantity: `52%`
  - UnitPrice: `48%`

---

## 📁 Estrutura do projeto

sales_prediction/

├── venv/

├── data/

│ └── data.csv

├── sales_prediction.ipynb

├── README.md

---

## ✨ Conclusão

Após a limpeza dos dados e otimização dos hiperparâmetros, o modelo apresentou desempenho robusto e baixo erro, ideal para aplicações preditivas em ambientes reais ou para fins educacionais.

---

# 🛒 Sales Revenue Prediction with Machine Learning

This project applies machine learning algorithms to predict sales revenue based on transaction data (quantity and unit price). The focus was to ensure accuracy and stability, especially after outlier removal.

## 📌 Objective
Predict total revenue per product using regression via the Random Forest algorithm.

---

## 🧠 Technologies used
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🔍 Pipeline steps

1. **Dataset download from Kaggle**
2. **Target variable creation (`Revenue`)**
3. **Outlier removal** based on extreme revenue values
4. **Modeling with Random Forest**
5. **Hyperparameter tuning with GridSearchCV**
6. **5-fold cross-validation**
7. **Evaluation using RMSE and feature importance analysis**
8. **Graphical visualizations (prediction vs actual, residuals)**

---

## 📊 Results

- **Average RMSE (5 folds)**: `0.0612`
- **Standard deviation**: `0.0147`
- **Best parameters**: `n_estimators=200, max_depth=None, min_samples_split=2`
- **Feature importance**:
  - Quantity: `52%`
  - UnitPrice: `48%`

---

## 📁 Project structure

sales_prediction/

├── venv/

├── data/

│ └── data.csv

├── sales_prediction.ipynb

├── README.md

---

## ✨ Conclusion

After cleaning and tuning, the model showed robust performance and low prediction error, making it suitable for production use or as an educational portfolio project.

---
