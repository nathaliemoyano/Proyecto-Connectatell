**Análisis Ptoyecto Conectatel:** 
\n**Objetivo:** identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

**Se Utilizaron 3 fuentes de datos:**
\n**plans.csv:** los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
\n**users_latam.csv:** información de clientes: edad, ciudad, fecha de registro, plan contratado.
\n**usage.csv:** el detalle de uso real: llamadas (duración) y mensajes (longitud).

**Etapas del Análisis**
-Carga y exploración inicial de los 3 datasets
-Limpieza de datos (nulos, sentinels, fechas inválidas)
-Integración de tablas
-Análisis estadístico y detección de outliers
-Segmentación por edad y nivel de uso
-Visualizaciones
-Conclusiones e insights de negocio



**Guía de reproducción, Necesitas:**
- Cargar 3 fuentes de datos: plans.csv, users_latam.csv, usage.csv
- Importar líbrerias :pandas, numpy, seaborn, matplotlib
- Abrir el notebook  y ejecutar todas las celdas en orden, desde la primera hasta la última, usando Run All o ejecutando celda por celda de arriba hacia abajo.
- Puedes abrir el proyecto en Google Colab o Jupyter
- Los datasets deben estar en una ruta específica como /datasets/
