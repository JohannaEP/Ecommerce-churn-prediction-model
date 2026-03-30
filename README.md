# 📊 E-commerce Churn Prediction Model  
Modelo completo para analizar, predecir y visualizar el churn (abandono de clientes) en plataformas de e‑commerce.  
Incluye EDA, limpieza, modelado, evaluación, segmentación y dashboard final con insights accionables.

---

## 🧠 Objetivo del Proyecto  
Identificar patrones de comportamiento que anticipen el abandono de clientes y construir un modelo predictivo que permita:

- Clasificar el riesgo de churn  
- Segmentar clientes según comportamiento  
- Generar estrategias de retención basadas en datos  
- Visualizar métricas clave para la toma de decisiones  

---

## 📂 Pipeline del Proyecto  
Este proyecto sigue un flujo profesional de machine learning:

1. **01_EDA.ipynb** → Análisis exploratorio  
2. **02_Data_Cleaning.ipynb** → Limpieza y preprocesamiento  
3. **03_Modeling.ipynb** → Entrenamiento de modelos  
4. **04_Evaluation.ipynb** → Evaluación y métricas  
5. **05_Segmentation.ipynb** → Segmentación de clientes (KMeans)  
6. **06_Dashboard_Insights.ipynb** → Dashboard final e insights  

---

## 🛠️ Tecnologías Utilizadas  

| Categoría | Herramientas |
|----------|--------------|
| Lenguaje | Python |
| Análisis | Pandas, NumPy |
| Visualización | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Clustering | KMeans |
| Modelos | Logistic Regression, Random Forest |
| Notebooks | Jupyter Notebook |

---

## 📁 Estructura del Repositorio  

Ecommerce-churn-prediction-model/
│
├── data/
│   ├── data.csv
│   ├── data_clean.csv
│   └── data_segmented.csv
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   ├── 03_Modeling.ipynb
│   ├── 04_Evaluation.ipynb
│   ├── 05_Segmentation.ipynb
│   └── 06_Dashboard_Insights.ipynb
│
├── models/
│   ├── churn_model.pkl
│   └── scaler.pkl
│
├── README.md
├── LICENSE
└── .gitignore

Código

---

## 📈 Resultados Principales  

### 🔍 **Variables más influyentes en el churn**
- Días desde la última compra  
- Frecuencia de compra  
- Total gastado  
- Actividad reciente  

### 🤖 **Mejor modelo**
**Random Forest**, con buen desempeño en:
- Recall (clave para detectar churn)
- AUC (capacidad discriminativa)
- F1 Score

### 👥 **Segmentación de clientes**
Se identificaron **3 segmentos** principales:

| Segmento | Características | Riesgo |
|----------|----------------|--------|
| 0 | Alta frecuencia, alto gasto | Bajo |
| 1 | Frecuencia media, gasto moderado | Medio |
| 2 | Alta inactividad, bajo gasto | Alto |

---

## 📊 Visualizaciones Incluidas  
- Distribución de churn  
- Importancia de variables  
- Matriz de confusión  
- Curva ROC  
- Scatterplot de segmentos  
- Perfil de clusters  

---

## 💡 Insights Clave  
- Los clientes con mayor inactividad presentan el mayor riesgo de churn.  
- La frecuencia de compra es un predictor crítico.  
- Los clientes de bajo gasto requieren estrategias de fidelización.  
- La segmentación permite personalizar campañas de retención.  

---

## 🎯 Recomendaciones de Negocio  
- **Segmento de alto riesgo:** descuentos personalizados, campañas urgentes.  
- **Segmento medio:** emails de reactivación, recomendaciones basadas en historial.  
- **Segmento bajo:** programas de fidelización y beneficios exclusivos.  
- Implementar alertas automáticas cuando un cliente supere cierto umbral de inactividad.  

---

## ▶️ Cómo Ejecutar el Proyecto  

1. Clonar el repositorio  
2. Instalar dependencias  
3. Ejecutar los notebooks en orden  
4. Revisar el dashboard final en el notebook 06  

---

## 📜 Licencia  
Este proyecto está bajo la licencia MIT.

---

## ✨ Autora  
**Johanna**  
Proyecto de análisis y machine learning aplicado a e‑commerce.
