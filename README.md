# 🧪 Regression with a Wild Blueberry Yield Dataset — Kaggle Competition

## 📘 Descripción del Notebook

Este notebook detalla el proceso completo seguido para abordar la competición de Kaggle, desde una pequeña exploración inicial de datos hasta el diseño del modelo final. Se hace especial énfasis en técnicas de optimización de modelos mediante **Optuna** y la creación de un **ensemble ajustado de CatBoost y LightGBM**.

---

## 🏁 Sobre la Competición

**Objetivo:**  
Predecir la produccion (`yield`) de de arándanos silvestres basados en datos del dataset.

**Métrica de evaluación:**  
> `Mean Absolute Error (MAE)` sobre un conjunto de test privado (80% del total oculto por Kaggle hasta el cierre).

**Estrategia clave:**  
> Optimizamos hiperparámetros con `Optuna`, y combinamos los mejores modelos con un ensemble ponderado para balancear rendimiento y robustez.

---

## 🏆 Resultado Final

- 📊 **Leaderboard privado:** `MAE = 241.409314`  
- 🥉 **Posición final:** **Top 3** de la clasificación general 🎉  

---

### 🔗 Tecnologías usadas

- Python (Pandas, Numpy)
- LightGBM y CatBoost
- Optuna
- Scikit-learn
- matplotlib
- seaborn
