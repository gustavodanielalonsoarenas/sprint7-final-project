# sprint7-final-project

Se desarrolla un análisis integral del comportamiento de clientes de telecomunicaciones con el fin de identificar patrones de uso, segmentar usuarios según su nivel de consumo y edad, y generar conclusiones accionables para optimizar la oferta de planes y la toma de decisiones comerciales.
El proyecto busca transformar datos operativos en insights estratégicos que permitan mejorar la retención de clientes, diseñar planes diferenciados y detectar oportunidades de negocio basadas en el uso real del servicio.

Datasets utilizados
El análisis se realizó utilizando tres fuentes principales:
- plans.csv: Información de los planes disponibles y sus características comerciales.
- users_latam.csv: Datos demográficos y de registro de los usuarios, incluyendo edad, ciudad, tipo de plan y fecha de alta.
- usage.csv: Historial de uso del servicio por usuario, incluyendo llamadas, mensajes y duración de las interacciones.

Etapas del análisis realizadas
1. Carga y exploración inicial
- Importación y revisión estructural de los datasets.
- Identificación de tipos de datos y valores faltantes.

2. Limpieza y preparación de datos
- Corrección de valores sentinnels (ej. edades inválidas).
- Tratamiento de valores nulos bajo criterio MAR (Missing At Random).
- Conversión y validación de variables de fecha, así como eliminación de valores fuera de rango.

3. Análisis exploratorio (EDA)
- Resúmenes estadísticos de variables numéricas.
- Evaluación de distribuciones mediante histogramas.
- Identificación visual y estadística de valores extremos (método IQR).

4. Segmentación de clientes
Clasificación por nivel de uso:
- Bajo uso
- Uso medio
- Alto uso
Segmentación por grupos de edad:
- Joven
- Adulto
- Adulto mayor

5. Visualización e interpretación
- Comparación de distribuciones por tipo de plan.
- Identificación de patrones de comportamiento y usuarios intensivos.
- Generación de conclusiones orientadas al negocio.

Guía breve de reproducción
1. Clonar o descargar el repositorio del proyecto.
2. Instalar dependencias principales:
  pip install pandas numpy matplotlib seaborn
3. Colocar los archivos CSV dentro del directorio /datasets/.
4. Ejecutar el notebook principal en orden secuencial:
- carga de datos
- limpieza
- análisis exploratorio
- agregaciones y segmentación
- visualizaciones finales
5. Revisar la sección de análisis ejecutivo para interpretar los resultados y recomendaciones de negocio.

Herramientas utilizadas: Python, Pandas, NumPy, Matplotlib, Seaborn
