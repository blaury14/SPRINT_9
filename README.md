# SPRINT 9: Optimización de Estrategias de Marketing y Ventas para una Tienda en Línea

## Descripción del Proyecto

En este proyecto, realizamos un análisis detallado de varias hipótesis para aumentar los ingresos de una gran tienda en línea y llevamos a cabo un test A/B para evaluar su impacto. La primera parte del proyecto se centró en priorizar las hipótesis utilizando los frameworks ICE y RICE. La segunda parte se enfocó en analizar los resultados del test A/B a través de diferentes métricas y visualizaciones.

## Objetivos del Proyecto

- Priorizar hipótesis de marketing y ventas utilizando los frameworks ICE y RICE.
- Realizar un test A/B para evaluar el impacto de las hipótesis seleccionadas.
- Analizar las métricas clave para determinar la efectividad de las estrategias.
- Proveer recomendaciones basadas en los resultados del test A/B.

## Pasos Realizados en el Proyecto

### Paso 1: Descarga y Preparación de los Datos

- **Archivos de Datos:**
  - `/datasets/project_sql_result_01.csv`: Datos sobre empresas de taxis y número de viajes.
  - `/datasets/project_sql_result_04.csv`: Datos sobre barrios de Chicago y número promedio de viajes.
  - `/datasets/project_sql_result_07.csv`: Datos sobre viajes desde el Loop hasta el Aeropuerto Internacional O'Hare.

- **Preparación de Datos:**
  - Cargamos los datos en DataFrames de pandas.
  - Revisamos y optimizamos los tipos de datos.
  - Filtramos y limpiamos los datos para análisis posteriores.

### Paso 2: Priorizar Hipótesis Utilizando ICE y RICE

- **Framework ICE:**
  - Impacto, Confianza y Esfuerzo fueron utilizados para calcular el puntaje ICE de cada hipótesis.
- **Framework RICE:**
  - Alcance (Reach), Impacto, Confianza y Esfuerzo fueron utilizados para calcular el puntaje RICE de cada hipótesis.
- **Resultados:**
  - Identificamos y priorizamos las hipótesis con mayor potencial para incrementar los ingresos.

### Paso 3: Análisis del Test A/B

- **Métricas Analizadas:**
  - Ingresos acumulados.
  - Tamaño promedio de pedido.
  - Tasas de conversión.
  - Análisis de anomalías.
- **Resultados:**
  - El grupo B mostró una tasa de conversión significativamente mayor y mayores ingresos acumulados en comparación con el grupo A.
  - Aunque el tamaño promedio de pedido del grupo B fue mayor, la diferencia no fue estadísticamente significativa.

### Paso 4: Recomendaciones Basadas en el Análisis

- **Implementar Estrategias del Grupo B:**
  - Las estrategias aplicadas al grupo B demostraron ser más efectivas.
  - Recomendamos implementar estas estrategias en toda la tienda para maximizar los ingresos.
- **Monitoreo Continuo:**
  - Es crucial seguir monitoreando las métricas clave para asegurarse de que las mejoras observadas durante el test A/B se mantengan a largo plazo.
- **Investigación de Anomalías:**
  - Las anomalías identificadas deben ser investigadas más a fondo para entender sus causas y tomar acciones correctivas si es necesario.

### Conclusión General del Proyecto

El análisis demostró que las estrategias aplicadas al grupo B fueron más efectivas en términos de tasa de conversión y ingresos acumulados. Recomendamos implementar estas estrategias a nivel general para maximizar los ingresos y mejorar la experiencia del usuario. Además, es importante continuar monitoreando las métricas clave y investigar cualquier anomalía para garantizar el éxito a largo plazo.

## Contribución

Si deseas contribuir a este proyecto, realiza un fork del repositorio y crea una pull request con tus mejoras. Asegúrate de que tu código sigue los lineamientos del proyecto y está bien comentado.

## Licencia

Este proyecto está bajo la licencia MIT. Para más detalles, consulta el archivo LICENSE.
