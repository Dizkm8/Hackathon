# Modelo de Predicción de Valores Faltantes en Sensores de Concentraducto

## Resumen
Este proyecto en Jupyter Notebook tiene como objetivo predecir valores faltantes cuando un sensor específico falla dentro del Concentraducto

Para abordar este problema, se utilizó Pandas y Matplotlib para la exploración de datos. Posteriormente, se entrenaron modelos de regresión lineal y no-lineal de ScikitLearn y XGBoost para predecir los valores faltantes.

## Requisitos Previos
1. Debido a estándares empresariales, se requiere Python 3.9. Verifique su versión con:
    ```bash
    python --version # Powershell
    python3 --version # Linux or Mac
    ```

2. Instale las bibliotecas de Python necesarias:
    ```bash
    pip install pandas numpy matplotlib scikit-learn xgboost jupyter
    ```
4. Ejecute el Jupyter Notebook `SolucionFinal.ipynb` utilizando el siguiente comando:
    ```bash
    jupyter notebook SolucionFinal.ipynb
    ```