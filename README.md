# Interconnect – Predicción de Cancelación de Clientes (Churn)

Este proyecto tiene como objetivo predecir si un cliente de la empresa de telecomunicaciones **Interconnect** cancelará su contrato, utilizando técnicas de **machine learning** y análisis de datos estructurados.

---

## Objetivo
Desarrollar un modelo capaz de anticipar la **cancelación de clientes (churn)** para ayudar a la empresa a reducir pérdidas y tomar decisiones proactivas de retención.

---

## Descripción del proyecto
El trabajo incluye el procesamiento, exploración y modelado de información proveniente de distintas fuentes de datos (`contract.csv`, `personal.csv`, `internet.csv`, `phone.csv`)

Se implementó un modelo de clasificación y validación cruzada.

---

## Tecnologías utilizadas
- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Optuna**
- **Matplotlib**, **Seaborn**
- **Pipeline & ColumnTransformer**
- **GridSearchCV**

---

## Proceso
1. **EDA (Exploratory Data Analysis)** – Identificación de valores ausentes, outliers y correlaciones.  
2. **Preprocesamiento** – Imputación, escalado y codificación de variables categóricas.  
3. **Pipeline automatizado** – Integración de todos los pasos en un flujo reproducible.  
4. **Entrenamiento y optimización** – Ajuste de hiperparámetros con *Optuna* y *GridSearchCV*.  
5. **Evaluación** – Validación cruzada y análisis de métricas (ROC-AUC, Accuracy, Recall, F1).

---

## Resultados
- Modelo final: **Random Forest Classifier**  
- Métrica principal: **ROC-AUC = 0.89**  
- Pipeline optimizado y reutilizable para nuevos datasets.
