# Data_Analyst_Challeng2
Descripción
Este proyecto forma parte de la iniciativa de Telecom X para comprender los factores que influyen en la evasión de clientes (churn). Utilizando técnicas de análisis de datos con R, se busca detectar patrones relevantes que permitan al equipo de ciencia de datos implementar modelos predictivos y estrategias de retención efectivas.

## Descripción del proyecto

* Identificar variables que explican el abandono de clientes.

* Detectar valores atípicos, nulos y errores de formato.

* Limpiar y preparar los datos para modelado predictivo.

* Explorar visualmente las diferencias entre clientes que se quedan y los que se van.


## Lenguaje: R

## Paquetes principales:

* tidyverse – manipulación y visualización de datos

* jsonlite – lectura de datos en formato JSON

* ggplot2 – visualización

* caret – modelado predictivo

* skimr, janitor – resumen y limpieza de datos

## Estructura del proyecto

├── TelecomX_Data.json   # Dataset principal (presente en GitHub)

├── TelecomX_diccionario.md  # Diccionario de datos

├── analisis_churn.R         # Script principal en R

├── README.md                # Este archivo


└── output/                  # Visualizaciones y reportes generados


## Carga de datos
* Lectura del archivo JSON desde GitHub usando fromJSON() y conversión a tibble.

* Limpieza de datos

* Eliminación de duplicados

* Conversión de textos mal formateados

* Manejo de valores nulos

* Normalización de categorías (Yes/No, etc.)

* Análisis exploratorio (EDA)

* Comparaciones por variable objetivo Churn

* Tablas de frecuencia y gráficos con ggplot2

## Detección de patrones relevantes

Modelado predictivo 
Preparación para modelos de clasificación con caret o tidymodels.

## Dataset
Los datos fueron proporcionados por Alura LATAM - Challenge Data Science, y contienen información anónima sobre:

* Datos personales y de contrato

* Servicios contratados (internet, teléfono)

* Historial de pagos

* Estado de cancelación (Churn)

## Autor
Nombre: Diewgo Daniel Gómez

## Rol: Asistente de Análisis de Datos – Telecom X

## Fecha: Junio 2025

## Notas finales
Este proyecto se enfoca en la etapa exploratoria y de preparación de datos. A futuro, se planea implementar un modelo de clasificación para predecir churn y sugerir acciones de retención personalizadas.
