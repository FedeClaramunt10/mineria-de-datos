# Minería de Datos

Trabajos de las materias Minería de Datos I y II de la Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial: proceso KDD, transformación de datos, reducción de dimensionalidad y evaluación de modelos de regresión.

## Notebooks

| Notebook | Contenido |
|----------|-----------|
| [Ejercicio1_Procesamiento_KDD.ipynb](notebooks/Ejercicio1_Procesamiento_KDD.ipynb) | Introducción al proceso KDD: comprensión y selección de datos. |
| [Ejercicio2_KDD_Churn.ipynb](notebooks/Ejercicio2_KDD_Churn.ipynb) | KDD sobre el dataset Telco Customer Churn (IBM), descargado de una URL pública. |
| [Ejercicio3_KDD_HeartDisease.ipynb](notebooks/Ejercicio3_KDD_HeartDisease.ipynb) | KDD sobre el dataset Heart Disease (UCI). |
| [Ejercicio4_Consumidores.ipynb](notebooks/Ejercicio4_Consumidores.ipynb) | KDD aplicado a datos de consumidores. |
| [Ejercicio_ACP_Consumo_Energetico.ipynb](notebooks/Ejercicio_ACP_Consumo_Energetico.ipynb) | Análisis de Componentes Principales (ACP) sobre hábitos de consumo energético residencial. |
| [TP_Metricas_de_Regresion.ipynb](notebooks/TP_Metricas_de_Regresion.ipynb) | Métricas de regresión (MAE, RMSE, R²) comparando modelos sobre datasets públicos de UCI: demanda de bicicletas compartidas y planta de ciclo combinado. |
| [Ejercicio1_BikeSharing.ipynb](notebooks/Ejercicio1_BikeSharing.ipynb) | Regresión sobre demanda de bicicletas compartidas (Bike Sharing). |
| [Ejercicio2_PotenciaElectrica.ipynb](notebooks/Ejercicio2_PotenciaElectrica.ipynb) | Regresión sobre el dataset Combined Cycle Power Plant. |
| [Ejercicios_Prediccion.ipynb](notebooks/Ejercicios_Prediccion.ipynb) | Ejercicios de conceptos de predicción y evaluación de modelos. |
| [Tarea2_Clase2_TP2.ipynb](notebooks/Tarea2_Clase2_TP2.ipynb) | Tarea 2: técnicas de transformación de datos. |
| [Tarea2_Ejercicio2.ipynb](notebooks/Tarea2_Ejercicio2.ipynb) | Tarea 2: ejercicio de transformación. |
| [Ejercicio1_NaiveBayes_GermanCredit.ipynb](notebooks/Ejercicio1_NaiveBayes_GermanCredit.ipynb) | Clasificación con Naive Bayes sobre German Credit (riesgo de crédito). |
| [Ejercicio2_NaiveBayes_Titanic.ipynb](notebooks/Ejercicio2_NaiveBayes_Titanic.ipynb) | Clasificación con Naive Bayes sobre el Titanic. |

### Entregas

| Archivo | Contenido |
|---------|-----------|
| [entregas/TP1_KDD_WineQuality_Claramunt.ipynb](entregas/TP1_KDD_WineQuality_Claramunt.ipynb) | TP evaluativo (unidades 1-3): proceso KDD completo sobre Wine Quality — EDA, limpieza, modelado y evaluación. |
| [entregas/TP1_Informe_Claramunt.docx](entregas/TP1_Informe_Claramunt.docx) | Informe del TP1 (Wine Quality). |
| [entregas/TP1_Regresion_Claramunt.ipynb](entregas/TP1_Regresion_Claramunt.ipynb) | TP de regresión (entregado): Bike Sharing y Combined Cycle Power Plant. |

Las figuras del TP1 (distribuciones, correlaciones, importancias, estructura del árbol) están en `figuras/`.

Todos los notebooks se publican ejecutados, con salidas y gráficos, y se pueden leer directamente en GitHub. Los que usan datasets externos los descargan de URLs públicas (GitHub/UCI); no se requieren archivos locales para ejecutarlos.

## Datos

- `data/dataset_streaming_usuarios.json`: base de 8.160 usuarios de una plataforma de streaming (edad, país, plan de suscripción, tiempo de visualización, etc.) utilizada en el TP Integrador de Minería de Datos I.
- `data/winequality-red.csv`: Wine Quality (UCI) — TP1 evaluativo.
- `data/bike_sharing/`: Bike Sharing (`day.csv`, `hour.csv`) — TP de regresión.
- `data/combined_cycle_power_plant/`: Combined Cycle Power Plant (UCI) — TP de regresión.
- `data/german.data` y `data/titanic.csv`: datasets de clasificación (Naive Bayes).
- `data/metricas.json`: métricas registradas del TP1.

## Informes

- `informes/informe_final_TP_streaming.docx` — Informe ejecutivo del TP Integrador de Minería de Datos I: análisis de comportamiento de usuarios de streaming (calidad de datos, EDA, escalamiento y PCA, conclusions y recomendaciones).
- `informes/TP_ACP_Consumo_Energetico.docx` / `.pdf` — Informe académico de ACP: análisis de componentes principales sobre consumo energético residencial por tamaño de familia e ingresos.

## Cómo ejecutar los notebooks

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
jupyter notebook notebooks/TP_Metricas_de_Regresion.ipynb
```

## Temas cubiertos

- Proceso KDD: selección, limpieza y preparación de datos
- Análisis exploratorio de datos (EDA)
- Reducción de dimensionalidad con ACP (PCA)
- Escalamiento y transformación de variables
- Métricas de evaluación de regresión: MAE, RMSE, R²
- Validación cruzada y comparación de modelos
- Modelos de regresión: lineal, árboles y boosting
- Clasificación con Naive Bayes

## Licencia

MIT
