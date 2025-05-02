# 🔄 Predicción de Fuga de Clientes con Interpretación SHAP

Este proyecto implementa un flujo completo de análisis de fuga de clientes (churn) utilizando un modelo de Random Forest, balanceo de clases con SMOTE y explicaciones con SHAP para interpretar los resultados.

## 📌 Descripción general

- **Modelo utilizado**: Random Forest Classifier
- **Preprocesamiento**:
  - Estandarización de variables numéricas
  - Codificación One-Hot para variables categóricas
  - Variables binarias sin transformación
- **Manejo de desbalanceo**: SMOTE
- **Validación**: Cross-validation estratificada (K-Fold) para encontrar el threshold que maximiza F1
- **Interpretabilidad**: SHAP para explicar tanto la importancia global como local de las variables

## 📁 Archivos del repositorio

- `churn_analysis_pipeline.ipynb`: Notebook principal con todo el flujo de trabajo
- `data/Customer-Churn-Records.csv`: Dataset de ejemplo (puedes reemplazarlo por uno simulado si no puedes compartir datos reales)
- `requirements.txt`: Paquetes necesarios para ejecutar el proyecto
- `.gitignore`: Archivos que se excluyen del control de versiones

## ⚙️ Instalación

1. Clonar el repositorio:
```bash
git clone https://github.com/osvaldovegacasanova/churn_con_shap.git
cd nchurn_con_shap
