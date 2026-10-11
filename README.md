# Tablero de Seguros

## Descripción

Aplicación interactiva desarrollada con Streamlit para explorar datos de una cartera de seguros, analizar siniestros y calcular primas.

## Funcionalidades

* Filtros para explorar la cartera de seguros.
* Indicadores clave de exposición, siniestros, frecuencia, severidad y prima pura.
* Gráficos para analizar los datos.
* Calculadora de cotización que compara primas estimadas mediante distintos métodos.

## Tecnologías

* Python
* Streamlit
* Pandas
* NumPy
* Matplotlib
* Statsmodels
* PyArrow

## Ejecución local

1. Clonar o descargar este repositorio.

2. Instalar las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

3. Ejecutar la aplicación:

   ```bash
   streamlit run app_streamlit.py
   ```

## Estructura del proyecto

* `app_streamlit.py`: aplicación principal.
* `requirements.txt`: dependencias de Python.
* `datos/datos.parquet`: conjunto de datos utilizado por la aplicación.
* `.gitignore`: archivos excluidos del repositorio.
