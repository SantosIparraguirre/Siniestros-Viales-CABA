# <p align=center>Siniestros viales en la Ciudad Autónoma de Buenos Aires</p>

![alt text](Imagenes/image.jpg)

### Introducción

El **Observatorio de Movilidad y Seguridad Vial (OMSV)**, dependiente de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires, ha solicitado un proyecto de análisis de datos con el objetivo de proporcionar información crucial que permita a las autoridades locales tomar medidas para reducir la cantidad de víctimas fatales en siniestros viales. Este proyecto utiliza un dataset proporcionado por el OMSV, que abarca los **homicidios en siniestros viales** ocurridos en Buenos Aires durante el período 2016-2021.

### Descripción del Proyecto
El objetivo del proyecto es analizar los datos de siniestros viales en Buenos Aires, identificar patrones y tendencias clave, y ofrecer recomendaciones basadas en los insights obtenidos. El dataset utilizado está en formato xlsx y contiene dos hojas: *"hechos"* y *"víctimas"*.

### Tecnologías y Herramientas Utilizadas
- **Python** (pandas, matplotlib, seaborn): Utilizado para el análisis exploratorio de datos (EDA).
- **Power BI:** Utilizado para el diseño y desarrollo del dashboard interactivo.

### Metodología Aplicada

#### Análisis Exploratorio de Datos (EDA):
Se realizó un EDA exhaustivo utilizando Python en un Jupyter Notebook, donde se limpiaron, exploraron y visualizaron los datos para identificar patrones y tendencias clave.

1) **Importación y limpieza de datos:**
- Importación de los datos desde un archivo excel.
- Revisión y limpieza de los datos mediante un análisis preliminar.

2) **Análisis descriptivo:**
- Cálculo de estadísticas descriptivas para comprender mejor la distribución de los datos.
- Creación de visualizaciones iniciales para identificar patrones y tendencias generales.

3) **Visualización de datos:**
- Uso de bibliotecas como matplotlib y seaborn para crear gráficos que permitan visualizar las relaciones y tendencias en los datos.
- Gráficos de barras, histogramas y mapas de calor para identificar correlaciones y posibles causas de los siniestros viales.
- Visualización de los datos segmentados por diferentes variables como tipo de vehículo, rango etario, y tipo de vía.

4) **Identificación de KPIs:**

- Definición de indicadores clave de rendimiento **(KPIs)** relevantes para el análisis, como la tasa de homicidios en siniestros viales, cantidad de accidentes de motociclistas, y cantidad de accidentes en avenidas.

#### Diseño del Dashboard:

1) **Importación de Datos:**

- Importación de los datos limpios y procesados desde Python a Power BI.

2) **Desarrollo de Medidas y Transformaciones:**

- Creación de medidas y cálculos personalizados para proporcionar información detallada y precisa.
- Transformaciones de datos para agregar nuevas columnas calculadas que ayuden a segmentar y analizar los datos de manera más efectiva.
- Cálculo de porcentajes, promedios y tasas de accidentes para distintos segmentos y periodos.

3) **Creación de Visualizaciones:**

- Diseño de visualizaciones interactivas que permitieran a los usuarios explorar los datos de manera dinámica.
- Uso de gráficos de líneas, gráficos de barras, gráficos circulares y mapas para representar diferentes aspectos de los siniestros viales.

4) **Configuración de Filtros:**

- Implementación de filtros para permitir a los usuarios ajustar la visualización de los datos según diferentes criterios como año, tipo de vía y tipo de vehículo.

5) **KPIs:**

- Representación de los indicadores clave de rendimiento (KPIs) utilizando medidores y tarjetas de varias filas.
- Medidores para mostrar el progreso hacia los objetivos definidos, como la reducción de la tasa de homicidios y accidentes mortales.
- Tarjetas de varias filas para presentar información detallada y resumida de los KPIs, facilitando la comprensión de los resultados.

6) **Interactividad y Navegabilidad:**

- Configuración de interacciones entre gráficos para mejorar la navegabilidad y facilitar la interpretación de los datos.
- Implementación de enlaces y botones de navegación dentro del dashboard para una experiencia de usuario más fluida.

### Conclusiones y recomendaciones

El análisis realizado sobre los datos reveló insights críticos que pueden guiar la implementación de políticas y medidas de seguridad vial más efectivas. La reducción significativa de accidentes durante la pandemia y el aumento de siniestros en ciertos períodos destacan la importancia de estrategias adaptativas. La alta proporción de víctimas masculinas y la peligrosidad de las avenidas subrayan la necesidad de campañas de concientización y mejoras en la infraestructura vial. Los jóvenes motociclistas y la estacionalidad de los accidentes indican áreas clave para intervenciones específicas. Las recomendaciones derivadas de este análisis, como controles de alcoholemia, educación vial, y mejoras en la señalización, tienen el potencial de reducir significativamente la tasa de siniestros viales y salvar vidas.