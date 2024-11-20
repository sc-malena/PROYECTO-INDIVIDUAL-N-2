
# Conexión Inclusiva 2024
### Presentación
Conexión Inclusiva 2024 es un proyecto destinado a mejorar la conectividad a Internet en las provincias de Argentina con menor acceso. Dado que la conectividad es un factor clave para el desarrollo económico y 
social, el proyecto busca implementar soluciones tecnológicas innovadoras, como la expansión de infraestructura de fibra óptica y la implementación de tecnologías satelitales, para mejorar el acceso a internet 
en zonas rurales y menos urbanizadas.
![Logo empresa](C:\Users\malen\OneDrive\Escritorio\proyecto n°2\DALL·E 2024-11-19 23.55.23 - Logo design for a company called 'Conecta Futuro' without any text. The logo should symbolize connectivity and the future of the internet. Incorporate.webp)

Este proyecto es liderado por Conecta Futuro, una empresa con una fuerte visión de inclusión digital, comprometida con reducir la brecha digital y garantizar el acceso a Internet en toda la Argentina, 
especialmente en provincias que presentan baja conectividad en comparación con otras regiones del país.

## Objetivo del Proyecto
La empresa Conecta Futuro busca invertir en el despliegue de tecnología de acceso a Internet en las provincias con menor conectividad, priorizando las zonas rurales y menos urbanizadas. El análisis se centra 
en identificar las áreas con mayor potencial de inversión y medir el impacto de las mejoras en conectividad, para asegurar el retorno de inversión y el éxito de la iniciativa.

## Transformación de los Datos
Datos utilizados
El análisis se basa en un conjunto de datos proporcionados por el gobierno de Argentina sobre telecomunicaciones, que incluye información sobre los accesos a Internet, las velocidades de conexión, 
y las tecnologías utilizadas en las diferentes provincias del país.

## Proceso de Transformación
El proceso de transformación de los datos consistió en:

- Limpieza de los datos: Se eliminaron las columnas vacías, los valores nulos y las columnas irrelevantes para enfocar el análisis en las variables que impactan directamente en la conectividad.
Reemplazo de valores incorrectos: Se realizaron ajustes a las columnas con datos erróneos o inconsistentes, como valores de velocidad incorrectos o valores nulos en algunas provincias.
- Normalización y formateo: Se homogeneizaron los datos para facilitar su análisis y visualización.
Para más detalles sobre el proceso de transformación de los datos, ver el archivo etl_y_EDA.ipynb.

### Análisis Exploratorio de Datos (EDA)
#### Preguntas clave
-¿En qué zonas conviene invertir?
-¿Qué acceso existe a internet en cada provincia?
-¿Qué velocidad de conexión se recomienda implementar?
-¿Cuáles son las provincias con mayor demanda y cuáles con mayor necesidad de inversión?

#### Variables clave analizadas
-Velocidad de conexión
-Accesos a Internet
-Provincias con baja conectividad

### Principales hallazgos:
-Las provincias más urbanizadas, como Buenos Aires, Córdoba, y Santa Fe, presentan mayores niveles de acceso a Internet y velocidades más rápidas, pero la competencia también es más alta.
-Las provincias con menor conectividad, como Catamarca, Formosa, Santa Cruz, y Tierra del Fuego, muestran una alta demanda insatisfecha, lo que representa una oportunidad para mejorar la infraestructura y acceso a Internet.
-La velocidad de conexión varía significativamente entre provincias, siendo las zonas más densamente pobladas las que tienen una mayor velocidad promedio, mientras que las zonas rurales y menos urbanizadas tienen una conexión más lenta.

#### Visualización: Dashboard Interactivo
El análisis se complementa con un dashboard interactivo que muestra los siguientes indicadores clave:

-Accesos por Provincia: Visualiza el número total de accesos a Internet por provincia, lo que permite identificar las regiones con mayor demanda de acceso.
-Velocidad Promedio por Provincia: Un gráfico que compara las velocidades promedio de Internet entre las distintas provincias, destacando las que necesitan mejoras.
-Accesos por Tipo de Tecnología: Distribuye los accesos según las tecnologías disponibles (ADSL, Cablemodem, etc.), permitiendo analizar la prevalencia de cada tipo de conexión.

## Conclusiones y Recomendaciones
Con base en el análisis, las siguientes recomendaciones son clave para el éxito del proyecto Conexión Inclusiva 2024:

-Ampliar la infraestructura en provincias con baja conectividad, como Catamarca, Formosa, Santa Cruz, y Tierra del Fuego, donde existe una alta demanda insatisfecha.
-Mejorar las velocidades de conexión en las zonas rurales que aún cuentan con conexiones lentas y limitadas.
-Evaluar estrategias de inversión en zonas con alta densidad de población para reducir la brecha de acceso y asegurar que la demanda de internet sea satisfactoriamente cubierta.

### Archivo del Proyecto
etl_y_EDA.ipynb: Proceso de transformación de los datos y análisis exploratorio de los datos.

### Tecnologías utilizadas

- **Python**: Para el desarrollo de la lógica del sistema y el procesamiento de datos.
- **Pandas**: Para la manipulación y transformación de datos.
- **PowerBi**: Para la creación del Dashboard Interactivo.


### Autores
Malena Sosa.
