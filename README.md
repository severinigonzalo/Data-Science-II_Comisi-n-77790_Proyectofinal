# 📊 Proyecto de Analítica Predictiva: Clasificación de Gravedad del Delito (LAPD Data)

## 📝 Resumen del Proyecto
Este proyecto desarrolla un pipeline completo de Ciencia de Datos y Machine Learning para predecir el nivel de riesgo y severidad de los delitos en la ciudad de Los Ángeles, utilizando el dataset histórico oficial del Departamento de Policía de Los Ángeles (LAPD). 

A través de un criterio operativo basado en el impacto delictivo, se implementó un modelo avanzado **XGBoost** que clasifica los incidentes en **Alta Gravedad** (delitos que atentan contra la integridad física o psicológica de las personas) y **Baja Gravedad** (delitos de índole patrimonial, material o administrativo). El algoritmo alcanzó un **ROC-AUC definitivo de 0.7571**, consolidándose como una herramienta predictiva sólida, con alto potencial para la optimización de recursos policiales (*Smart Policing*) y el diseño de políticas públicas de prevención urbana.

---

## 📂 Estructura y Guía de Contenidos

Para facilitar la evaluación y el entendimiento del proyecto, la documentación se ha distribuido estratégicamente en dos piezas principales dentro de este repositorio:

### 1. 📓 Jupyter Notebook (`.ipynb` / Google Colab)
En el código fuente principal encontrarás el desarrollo técnico paso a paso (EDA, Ingeniería de Atributos con codificación estratificada, Entrenamiento con Validación Cruzada, Optimización de Hiperparámetros con `RandomizedSearchCV`, Evaluación de métricas y Mapeo espacial interactivo con `Folium`). 
* **Nota para el lector:** Cada bloque de código cuenta con **descripciones introductorias ejecutivas en celdas de Markdown**, ideales para seguir el hilo lógico del procesamiento y la ejecución en tiempo real dentro del entorno de desarrollo.

### 2. 🖨️ Presentación Ejecutiva (PPT )
Si buscás profundizar en los fundamentos teóricos, la defensa metodológica y las conclusiones de negocio, te recomendamos revisar la presentación.
* **Nota para el lector:** En la **PPT se encuentra una descripción técnica mucho más detallada y extensa**. Allí se profundiza rigurosamente en el comportamiento de las métricas de la Matriz de Confusión, el análisis sociológico del gráfico de Importancia de Variables (Feature Importance), la interpretación académica de la Curva ROC y el impacto estratégico/económico de transferir este algoritmo a la gestión pública de ciudades inteligentes.

---

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.12
* **Manipulación de Datos:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn, XGBoost
* **Visualización de Datos:** Matplotlib, Seaborn, Folium (Mapas interactivos)
