# Predicción de Churn en Gimnasios 🏋️‍♂️

Este proyecto aplica **Machine Learning** para analizar y predecir el *churn* (deserción) de clientes en un gimnasio, utilizando datos reales. Se realiza un análisis exploratorio, visualización y entrenamiento de modelos predictivos.

## 📋 Descripción

El objetivo es identificar los factores que influyen en que un cliente deje de asistir al gimnasio y desarrollar un modelo capaz de predecir esta deserción con alta precisión.

El flujo de trabajo incluye:

1. **Carga y exploración de datos**: Análisis de la distribución de variables y diferencias entre clientes que se quedan y los que se van.
2. **Visualización**: Histogramas, gráficos comparativos y análisis de correlaciones.
3. **Preprocesamiento**: Escalado de variables y separación en conjuntos de entrenamiento y prueba.
4. **Modelado**: Implementación de modelos de clasificación como:
   - Regresión Logística
   - Random Forest
5. **Evaluación de modelos**: Métricas como precisión (*accuracy*), *precision* y *recall*.
6. **Clustering**: Agrupación de clientes mediante *K-Means* y *Hierarchical Clustering* para encontrar patrones ocultos.

## 📂 Estructura del repositorio
├── Proyecto_ML.ipynb # Notebook con todo el análisis y modelado
├── README.md # Descripción del proyecto
├── requirements.txt # Librerías necesarias para ejecutar el proyecto
└── data/
└── gym_churn_us.csv # Dataset utilizado (no incluido por privacidad)


## 🚀 Instalación y uso

1. Clona el repositorio:
   ```bash
   git clone https://github.com/usuario/nombre-del-repo.git
   cd nombre-del-repo

2. Instala las dependencias
   ```bash
   pip install -r requirements.txt

4. Abre el notebook
   ```bash
   jupyter notebook Proyecto_ML.ipynb


## 📊 Tecnologías utilizadas
  1. Python 3
  
  2. Pandas, NumPy
  
  3. Matplotlib, Seaborn
  
  4. Scikit-learn
  
  5. SciPy

## 📈 Resultados
  1. Identificación de variables clave en la deserción de clientes.

  2. Modelos con métricas competitivas en precision y recall.

  3. Segmentación de clientes en grupos con patrones de comportamiento diferenciados.

## 📄 Licencia
Este proyecto se distribuye bajo la licencia MIT.
