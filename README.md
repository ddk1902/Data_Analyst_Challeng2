# 📊 Proyecto: Análisis de Evasión de Clientes (Churn) – Telecom X

## Descripción

Este proyecto forma parte de la iniciativa de **Telecom X** para comprender los factores que influyen en la **evasión de clientes (churn)**. Utilizando técnicas de análisis de datos con **Python**, se busca detectar patrones relevantes que permitan al equipo de ciencia de datos implementar modelos predictivos y estrategias de retención efectivas.

---

## Objetivos

- Identificar variables que explican el abandono de clientes.
- Detectar valores atípicos, nulos y errores de formato.
- Limpiar y preparar los datos para modelado predictivo.
- Explorar visualmente las diferencias entre clientes que se quedan y los que se van.

---

## Tecnologías utilizadas

- **Lenguaje**: Python 3.x
- **Librerías principales**:
  - `pandas` – manipulación de datos
  - `numpy` – análisis numérico
  - `matplotlib` y `seaborn` – visualización de datos
  - `requests` y `json` – carga de datos desde APIs o GitHub
  - `scikit-learn` – modelado predictivo
  - `category_encoders` – codificación de variables categóricas (opcional)

---

## Estructura del proyecto

```
├── TelecomX_Data.json       # Dataset principal (presente en GitHub)

├── TelecomX_diccionario.md  # Diccionario de datos

├── analisis_churn.py        # Script principal en Python

├── README.md                # Este archivo

└── output/                  # Visualizaciones y reportes generados
```

---

## Flujo de trabajo

1. **Carga de datos**  
   Lectura del archivo JSON directamente desde GitHub usando `requests` y conversión a `pandas.DataFrame`.

2. **Limpieza de datos**  
   - Eliminación de duplicados  
   - Conversión de campos numéricos mal formateados  
   - Manejo de valores nulos  
   - Normalización de categorías (`Yes`, `No`, etc.)

3. **Análisis exploratorio (EDA)**  
   - Comparaciones por variable objetivo `Churn`  
   - Visualización de distribuciones y relaciones  
   - Cálculo de correlaciones y estadísticas

##  Dataset

Los datos fueron proporcionados por [Alura LATAM - Challenge Data Science](https://github.com/alura-cursos/challenge2-data-science-LATAM), y contienen información anónima sobre:

- Datos personales y de contrato
- Servicios contratados (internet, teléfono)
- Historial de pagos
- Estado de cancelación (`Churn`)


## Autor

- **Nombre**: *Diego D. Gómez*
- **Rol**: Asistente de Análisis de Datos – Telecom X
- **Fecha**: Junio 2025

---

## Notas finales

Este proyecto se enfoca en la **etapa exploratoria y de preparación de datos**. A futuro, se planea implementar un modelo de clasificación para predecir churn y sugerir acciones de retención personalizadas.
