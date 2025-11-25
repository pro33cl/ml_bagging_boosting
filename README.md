# 🧠 Bagging y Boosting para Predicción en la Industria de Viajes

Notebook: ml_bagging_boosting.ipynb

📄 Descripción General

Este notebook desarrolla un proyecto completo de Machine Learning aplicado al sector de viajes, utilizando técnicas de Bagging y Boosting para predecir una variable objetivo relacionada con el comportamiento de clientes. Se abordan limpieza, ingeniería de características, selección de variables y modelado avanzado.

📂 Contenidos del Notebook

1️⃣ Definición del problema

- Análisis del contexto del negocio y relevancia del problema.
- Descripción de las variables y objetivo a predecir.

2️⃣ Carga y preparación de datos

- Importación de múltiples datasets.
- Eliminación y tratamiento de nulos, outliers y valores perdidos.
- Transformaciones iniciales para un mejor modelado.

3️⃣ Análisis exploratorio

- Distribuciones y estadísticos por variable.
- Visualización de correlaciones y relaciones clave.
- Identificación de patrones relevantes para el negocio.

4️⃣ Ingeniería de características

- Creación y selección de nuevas variables.
- Uso de análisis previo y expertise del negocio para definir features.
- Implementación de Sequential Feature Selector.

5️⃣ Modelos candidatos

- DummyRegressor como baseline.
- RandomForestRegressor (Bagging).
- Lasso como modelo lineal con regularización.
- XGBRegressor (Boosting).

6️⃣ Optimización y evaluación

- Tuning de hiperparámetros con GridSearchCV.
- Métricas de rendimiento: MAE, MSE, RMSE, R².
- Comparación final entre modelos.

7️⃣ Exportación

- Guardado del mejor modelo con joblib.dump().

🛠️ Tecnologías Utilizadas

- Python 3
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-Learn
- XGBoost
- Joblib

▶️ Cómo Ejecutar el Notebook

1. Clonar el repositorio:
   
- git clone <URL>
- cd <repo>

2. Instalar dependencias:
   
- pip install -r requirements.txt

3. Ejecutar:
   
- jupyter notebook ml_bagging_boosting.ipynb

🎯 Objetivo del Proyecto

Aplicar técnicas de Bagging y Boosting para construir un modelo predictivo robusto en un entorno de negocio real, seleccionando las mejores características y el modelo con mayor capacidad explicativa.

📬 Contacto

Proyecto desarrollado por Héctor Rubilar Valenzuela.
