## Bienvenidos al repositorio de Análisis de tendencias tecnológicas
En este repositorio podras encontrar un ejemplo de como realizar un análisis de tendencias tecnologicas por pais. en el cual tomaremos como ejemplo el pasi de Ecuador. y utilizaremos Pytrend y Pytorch.

____________________________________________________________________________________________
# Estructura del repositorio
____________________________________________________________________________________________
Se procede a relizar cambios significativos en la obtencion de datos y se realiza una simulación de obtencion de dato ya que no se ha logrado establecer conexion con google Trends

## Fase de cambio
### 3. Obtención de Datos (Simulación por Bloqueo de API)
> **Nota Metodológica:** Durante la fase de extracción, se encontraron bloqueos de red persistentes al intentar acceder a los datos de Google Trends a través de la librería `pytrends`. Tras una depuración exhaustiva que incluyó el uso de proxies, timeouts, reintentos y el cambio a una red de datos móvil diferente, el problema persistió, sugiriendo un bloqueo a nivel de servicio fuera de nuestro control.
>
> Para no detener el progreso del proyecto y poder cumplir con los objetivos de análisis, visualización y modelado, se ha tomado la decisión pragmática de **generar un conjunto de datos simulado**. Este dataset imita fielmente la estructura (DataFrames, tipos de datos, rangos de valores) que `pytrends` devolvería, permitiendo el desarrollo completo de las fases posteriores del análisis.
