# Predicción de Satisfacción de Pasajeros de Aerolínea

Proyecto final de **Proyecto de Datos 2**, orientado a identificar los factores que determinan la satisfacción de los pasajeros, entrenar y comparar modelos de clasificación y priorizar mejoras de servicio por clase de cabina.

**Autores:** Vicente Jiménez, Agustín Trigo


## Estructura del Proyecto

* `airline_satisfaction.ipynb`: Notebook principal con limpieza, análisis exploratorio, entrenamiento de modelos, explicabilidad (SHAP) y análisis por clase de cabina.
* `requirements.txt`: Dependencias exactas del entorno Python.
* `versiones_ejecucion.json`: Registro de las versiones de las librerías principales utilizadas en la ejecución final.
* `train.csv` / `test.csv` / `sample_submission.csv`: Archivos de la competencia de Kaggle *Predicting Airline Satisfaction*. No se incluyen en el repositorio por tamaño; deben ubicarse en esta misma carpeta raíz antes de ejecutar el notebook.
* `figuras_presentacion/` y `resultados_modelos/`: Carpetas generadas automáticamente al ejecutar el notebook, donde se exportan los gráficos (`.png` / `.svg`) y las tablas de métricas (`.csv`).


## Instalación y Ejecución

**1. Configurar el entorno e instalar dependencias**

Abrir una terminal en la carpeta del proyecto y ejecutar lo siguiente para crear y activar el entorno virtual:

```bash
python -m venv .venv
.\.venv\Scripts\activate
```

Con el entorno activado, ejecutar lo siguiente para instalar las dependencias:

```bash
pip install -r requirements.txt
```

**2. Descargar los datos y ejecutar**

Descargar `train.csv`, `test.csv` y `sample_submission.csv` desde la competencia de Kaggle, dejarlos en la carpeta raíz y ejecutar todas las celdas de `airline_satisfaction.ipynb`:

https://www.kaggle.com/competitions/playground-series-s6e10