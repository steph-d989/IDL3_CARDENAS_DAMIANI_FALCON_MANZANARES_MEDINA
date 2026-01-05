# 📊 Modelo Predictivo de Compra de Seguro Vehicular

## 📌 Descripción general

Este proyecto tiene como objetivo desarrollar y evaluar un **modelo de Machine Learning** capaz de predecir si un cliente adquirirá o no un **seguro vehicular**, a partir de datos obtenidos mediante una encuesta estructurada. El modelo busca apoyar la **toma de decisiones comerciales**, permitiendo identificar clientes con alta probabilidad de conversión.

El enfoque combina **análisis de datos**, **ingeniería de variables**, **modelado predictivo**, **evaluación estadística** e **interpretación de resultados orientados al negocio**.

---

## 🎯 Objetivo del proyecto

Desarrollar un modelo predictivo confiable que permita:

* Identificar clientes con alta probabilidad de adquirir un seguro vehicular.
* Optimizar estrategias comerciales y de marketing.
* Reducir costos operativos al priorizar clientes con mayor potencial.

---

## 🗂️ Estructura del proyecto

```
IDL3_CARDENAS_DAMIANI_FALCON_MANZANARES_MEDINA/
│
├── data/
│   ├── SEGUROS (respuestas).xlsx
│   ├── seguros_codificado.csv
│   ├── seguros_sintetico.csv
│   ├── seguros_mixto.csv
│
├── notebooks/
│   ├── SEGUROS_CODIFICADO.ipynb
│   ├── modelos_predictivos.ipynb
│
├── README.md
└── requirements.txt
```

---

## 📥 Dataset

* **Fuente:** Encuesta aplicada a clientes potenciales.
* **Tipo de datos:** Variables demográficas, preferencias, percepciones y comportamiento.
* **Target:** Variable binaria que indica si el cliente adquiere o no el seguro.

Adicionalmente, se trabajó con:

* **Datos sintéticos** (para ampliar el conjunto de datos).
* **Datos mixtos** (combinación de reales y sintéticos).

---

## 🔧 Preprocesamiento de datos

Las principales etapas incluyeron:

* Limpieza de datos y manejo de valores nulos.
* Codificación de variables categóricas (Label Encoding y variables dummy).
* Conversión de variables ordinales.
* Normalización de variables numéricas.
* Generación de datasets sintéticos para mejorar la robustez del modelo.

---

## 🤖 Modelos de Machine Learning

Se evaluaron diferentes enfoques, destacando:

* **Random Forest Classifier** (modelo principal).
* Comparación con modelos base.

### Justificación del modelo elegido

Random Forest fue seleccionado debido a:

* Alta capacidad predictiva.
* Robustez frente a ruido.
* Capacidad de interpretar la importancia de variables.

---

## 📈 Evaluación del modelo

El desempeño del modelo se evaluó utilizando un conjunto de prueba independiente mediante:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC
* Matriz de confusión

Los resultados demostraron una **alta capacidad de generalización** y una **buena discriminación entre clientes compradores y no compradores**.

---

## 🔍 Importancia de variables

Se analizó la relevancia de cada variable para identificar los factores más influyentes en la decisión de compra, generando **insights estratégicos** útiles para el área comercial.

---

## 🧪 Simulación con clientes nuevos

El modelo permite realizar predicciones individuales, entregando:

* Clasificación (Compra / No compra).
* Probabilidad de compra asociada.

Esto facilita su uso en **escenarios reales de negocio**.

---

## 💼 Impacto en el negocio

La implementación del modelo permite:

* Priorizar clientes con alta probabilidad de conversión.
* Optimizar campañas de ventas.
* Mejorar la eficiencia operativa.
* Reducir esfuerzos comerciales innecesarios.

---

## ⚖️ Consideraciones éticas

* Uso responsable de los datos.
* Protección de la información personal.
* Transparencia en el uso del modelo predictivo.

---

## 🛠️ Tecnologías utilizadas

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook / VS Code

---

## 📌 Conclusiones

El proyecto demuestra que el uso de técnicas de **Machine Learning aplicado al análisis comercial** puede generar valor real para la toma de decisiones, proporcionando modelos interpretables, precisos y alineados con objetivos estratégicos.

---

## 👩‍💻 Autores

Proyecto desarrollado como parte del curso **Proyecto Productivo IIA** – Instituto Continental, Perú (2025).
