# Proyecto de Análisis de Comportamiento de Clientes en Línea

Este es un proyecto de estudio que tiene como objetivo analizar el comportamiento de los clientes en línea durante los meses de noviembre y diciembre.

---

## Descripción del Proyecto

El equipo de marketing ha solicitado analizar:
1. Las tasas de compra por tipo de cliente.
2. La correlación más fuerte entre los tiempos invertidos en distintos tipos de página.
3. La probabilidad de alcanzar un objetivo de ventas bajo una nueva campaña.

---

## Instrucciones

### 1. Tasas de Compra
Calcula las tasas de compra para las sesiones de compras en línea por tipo de cliente (clientes recurrentes y nuevos) en noviembre y diciembre.
- Guarda el resultado en un diccionario llamado `purchase_rates` con el siguiente formato:

```python
purchase_rates = {"Returning_Customer": 0.254, "New_Customer": 0.276}
```

### 2. Correlación Más Fuerte
Determina la correlación más fuerte en el tiempo total invertido entre los tipos de página por parte de los clientes recurrentes durante noviembre y diciembre.
- Guarda el resultado en un diccionario llamado `top_correlation` con el siguiente formato:

```python
top_correlation = {"pair": (x_duration, y_duration), "correlation": 0.345}
```

### 3. Probabilidad de Ventas
Con una nueva campaña, se espera que la tasa de compra de los clientes recurrentes aumente en un 15%.
- Calcula la probabilidad de lograr al menos 100 ventas de 500 sesiones de compras en línea para los clientes recurrentes.
- Guarda el resultado en una variable llamada `prob_at_least_100_sales`.
- (Opcional) Traza un gráfico de distribución de probabilidad binomial para visualizar las posibilidades.

---

## Guías de Estudio
Puedes consultar los siguientes recursos de DataCamp para ayudarte con este proyecto:
- [Random Numbers and Probability](https://campus.datacamp.com/courses/introduction-to-statistics-in-python/random-numbers-and-probability-2?ex=13)
- [Correlation and Experimental Design](https://campus.datacamp.com/courses/introduction-to-statistics-in-python/correlation-and-experimental-design-4?ex=1)

---

## Requisitos

### Librerías
Asegúrate de tener instaladas las siguientes librerías:
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from scipy import stats
```

### Versión de Python
El proyecto fue desarrollado y probado en **Python 3.11.05**.

---

## Cómo Ejecutar el Proyecto
1. Clona este repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```
2. Asegúrate de tener las librerías requeridas instaladas.
3. Ejecuta el script en tu entorno local para analizar los datos y obtener los resultados.

---

## Notas
Este proyecto tiene fines educativos y es parte de un estudio sobre análisis estadístico y comportamiento de clientes en línea. Si tienes preguntas o sugerencias, no dudes en contribuir al repositorio o contactarme.

