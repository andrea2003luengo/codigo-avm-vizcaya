Trabajo de Fin de Máster (TFM) - Máster Universitario en Big Data y Ciencia de Datos

Este repositorio contiene el código, los archivos de Machine Learning y la aplicación web interactiva para la estimación de precios del mercado inmobiliario en la provincia de Vizcaya mediante una arquitectura de Stacking híbrido de dos niveles. Se pueden encontrar los siguientes archivos:
- `app.py`: Aplicación web interactiva desarrollada en Streamlit para la interacción del usuario.
- `predicción_del_mercado_inmobiliario.py`: Notebook de código con el flujo completo de minería de datos, preprocesamiento, ingeniería de características, optimización por Optuna y entrenamiento de los modelos.
- Modelos base, meta-modelos y codificaciones (`.joblib`): Archivos comprimidos correspondientes a los modelos de Nivel 0 (ElasticNet, Random Forest, LightGBM, XGBoost), los meta-expertos de Nivel 1 (Stacking híbrido) y las codificaciones mediante One-Hot Encoding y Target Encoding.
- `requirements.txt`: Librerías necesarias para la ejecución del entorno.

La aplicación web se encuentra disponible en el siguiente enlace público:
[Enlace a la app AVM Vizcaya](https://tasador-vizcaya-avm.streamlit.app/)
