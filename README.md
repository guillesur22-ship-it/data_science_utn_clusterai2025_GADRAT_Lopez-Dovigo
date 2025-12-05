# Proyecto de Data Science – ClusterAI 2025  
## Grupo 06 – Guillermo López Dovigo & Emilie Gadrat

---

##  Descripción general

Este repositorio contiene el trabajo final de la materia **Data Science – UTN BA (Clúster AI 2025)**.  
El objetivo del proyecto es desarrollar un **modelo predictivo capaz de estimar el precio de alojamientos de Airbnb** en diferentes ciudades de Estados Unidos, utilizando técnicas de Machine Learning.

El trabajo incluye:

- Limpieza de datos y transformación de variables  
- Análisis exploratorio (EDA)  
- Procesamiento de la columna *amenities*  
- Reducción de dimensionalidad mediante **PCA**  
- Entrenamiento de modelos de regresión:  
  - Regresión Lineal  
  - SVR (RBF)  
  - MLPRegressor (Red Neuronal Artificial)  
- Comparación de métricas (RMSE y R²)  
- Conclusiones finales

---

##  Archivos del repositorio

-  **Reporte PDF del proyecto:**  
  `clusterai_reporte_LOPEZ DOVIGO_GADRAT.pdf`

-  **Notebook de EDA + Machine Learning (comprimido):**  
  `clusterai_LOPEZ_DOVIGO_GADRAT_eda_Machine_learning.zip`  
  *(Descomprimir para visualizar el notebook .ipynb con todo el análisis completo.)*

---

##  Resultados principales

- El mejor desempeño del modelo se obtuvo con **MLPRegressor con PCA**, alcanzando:  
  - RMSE ≈ **48.8 USD**  
  - R² ≈ **0.508**

- Los modelos no lineales (SVR y MLP) superaron ampliamente a la regresión lineal.

- El uso de **PCA redujo el error**, mejoró la estabilidad del entrenamiento y disminuyó el riesgo de sobreajuste.

---

##  Tecnologías utilizadas

- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

##  Integrantes

- **Guillermo López Dovigo**  
- **Emilie Gadrat**

---

##  Contacto

Para consultas académicas, comunicarse con cualquiera de los integrantes del grupo.

