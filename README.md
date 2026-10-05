# Minería de Datos

Trabajos de las materias Minería de Datos I y II de la Tecnicatura en Análisis de Datos e Inteligencia Artificial: proceso KDD, transformación de datos, reducción de dimensionalidad y evaluación de modelos de regresión.

## Notebooks

| Notebook | Contenido |
|----------|-----------|
| [Ejercicio1_Procesamiento_KDD.ipynb](notebooks/Ejercicio1_Procesamiento_KDD.ipynb) | Introducción al proceso KDD: comprensión y selección de datos. |
| [Ejercicio2_KDD_Churn.ipynb](notebooks/Ejercicio2_KDD_Churn.ipynb) | KDD sobre el dataset Telco Customer Churn (IBM), descargado de una URL pública. |
| [Ejercicio3_KDD_HeartDisease.ipynb](notebooks/Ejercicio3_KDD_HeartDisease.ipynb) | KDD sobre el dataset Heart Disease (UCI). |
| [Ejercicio4_Consumidores.ipynb](notebooks/Ejercicio4_Consumidores.ipynb) | KDD aplicado a datos de consumidores. |
| [Ejercicio_ACP_Consumo_Energetico.ipynb](notebooks/Ejercicio_ACP_Consumo_Energetico.ipynb) | Análisis de Componentes Principales (ACP) sobre hábitos de consumo energético residencial. |
| [TP_Metricas_de_Regresion.ipynb](notebooks/TP_Metricas_de_Regresion.ipynb) | Métricas de regresión (MAE, RMSE, R²) comparando modelos sobre datasets públicos de UCI: demanda de bicicletas compartidas y planta de ciclo combinado. |

Todos los notebooks se publican ejecutados, con salidas y gráficos, y se pueden leer directamente en GitHub. Los que usan datasets externos los descargan de URLs públicas (GitHub/UCI); no se requieren archivos locales para ejecutarlos.

## Datos

- `data/dataset_streaming_usuarios.json`: base de 8.160 usuarios de una plataforma de streaming (edad, país, plan de suscripción, tiempo de visualización, etc.) utilizada en el TP Integrador de Minería de Datos I.

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

## Licencia

MIT
