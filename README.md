# Análisis para la Expansión de Laboratorios en América Latina

**Autor**: Ignacio Cardetti  
**Carrera**: Data Analytics  
**Módulo**: 4  
**Cohorte**: DA-FT05  
**Institución**: BIOGENESYS  
**Fecha de Entrega**: 23/08/2024

[![Captura-de-pantalla-2024-10-31-184226.png](https://i.postimg.cc/nrQBkkpn/Captura-de-pantalla-2024-10-31-184226.png)](https://postimg.cc/2Lr1jn1t)


---

## Índice

- [Introducción](#introducción)
- [Desarrollo del Proyecto](#desarrollo-del-proyecto)
  - [Importación y Preparación de Datos](#importación-y-preparación-de-datos)
  - [Análisis del Comportamiento de la Pandemia](#análisis-del-comportamiento-de-la-pandemia)
  - [Impacto de la Temperatura](#impacto-de-la-temperatura)
  - [Urbanización y Densidad Poblacional](#urbanización-y-densidad-poblacional)
  - [Estrategias de Vacunación](#estrategias-de-vacunación)
  - [Condiciones Preexistentes](#condiciones-preexistentes)
  - [Tasa de Letalidad y Reducción de Casos](#tasa-de-letalidad-y-reducción-de-casos)
  - [Situación Actual](#situación-actual)
- [EDA e Insights](#eda-e-insights)
  - [Exploración de Datos Inicial (EDA)](#exploración-de-datos-inicial-eda)
  - [Principales Insights Obtenidos](#principales-insights-obtenidos)
- [Análisis del Dashboard](#análisis-del-dashboard)
  - [Página 1: Portada](#página-1-portada)
  - [Página 2: Análisis de COVID-19](#página-2-análisis-de-covid-19)
  - [Página 3: Contexto de los Países](#página-3-contexto-de-los-países)
- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
  - [Conclusiones Estratégicas](#conclusiones-estratégicas)
- [Reflexión Personal](#reflexión-personal)
- [Extra Credit](#extra-credit)

---

## Introducción

**BIOGENESYS** es una empresa del rubro farmacéutico que busca identificar las ubicaciones óptimas para la expansión de laboratorios farmacéuticos, basándose en el análisis de datos de incidencia de COVID-19, tasas de vacunación, y la disponibilidad de infraestructuras sanitarias. La meta es optimizar la respuesta a los efectos de la pandemia y post pandemia con el fin de mejorar el acceso a las vacunas.

## Desarrollo del Proyecto

### Importación y Preparación de Datos

Se trabajó con un conjunto de datos que incluía información sobre la evolución de la pandemia en diversos países latinoamericanos. Estos datos se prepararon cuidadosamente para asegurar su integridad, lo que incluyó la eliminación de valores nulos y anómalos, y la transformación de las variables para su posterior análisis.

### Análisis del Comportamiento de la Pandemia

El análisis se enfocó en el comportamiento de los casos de COVID-19 a lo largo del tiempo, tanto de forma semanal como anual. Este análisis reveló una tendencia general a la disminución de casos y muertes conforme avanzaba el tiempo, lo que sugiere que las estrategias de control y vacunación han sido efectivas en la región.

### Impacto de la Temperatura

Se investigó la relación entre la temperatura promedio y la evolución de los casos de COVID-19. Se observó que, aunque la temperatura ha ido en aumento, los casos han disminuido, especialmente después de picos notables antes de marzo, lo que podría estar vinculado a la efectividad de las campañas de vacunación.

### Urbanización y Densidad Poblacional

Se analizó el impacto de la urbanización y la densidad poblacional en la propagación del virus. Chile, con un alto porcentaje de población urbana, mostró una mayor propagación del virus. Este análisis también incluyó la distribución de la población por grupos etarios en países con altas tasas de mortalidad, lo que ayudó a identificar a los grupos más vulnerables.

### Estrategias de Vacunación

Las estrategias de vacunación se compararon entre los países, revelando que Brasil y Colombia son los que más podrían beneficiarse de una intervención debido a su baja tasa de vacunación en relación con su población. Estos hallazgos sugieren que la expansión de los laboratorios en estos países podría tener un impacto significativo en la lucha contra la pandemia.

### Condiciones Preexistentes

Se estudió la prevalencia de condiciones de salud preexistentes, como la diabetes y el tabaquismo, en los países con las tasas de mortalidad más altas. Se descubrió que México y Brasil tienen una alta prevalencia de diabetes, mientras que Chile y Argentina presentan mayores tasas de tabaquismo, lo que podría haber contribuido a las altas tasas de mortalidad en estos países.

### Tasa de Letalidad y Reducción de Casos

Se calculó la tasa de letalidad del COVID-19 en cada país, lo que mostró una disminución en la letalidad reciente, posiblemente debido a la efectividad de las vacunas. Además, se analizó la evolución de los casos activos y recuperados, demostrando que los casos activos han disminuido mientras que los recuperados han aumentado, lo que refuerza la importancia de la vacunación.

### Situación Actual

El análisis concluyó con una comparación de la situación actual de los países seleccionados, teniendo en cuenta los casos activos, recuperados y fallecidos. Brasil emergió como el país prioritario para la expansión, debido a su alta cantidad de casos confirmados y muertes, así como a su relativamente baja tasa de vacunación.

## EDA e Insights

### Exploración de Datos Inicial (EDA)

Para comprender mejor la naturaleza y el comportamiento de los datos relacionados con la pandemia de COVID-19 en América Latina, se realizó un análisis exploratorio exhaustivo. Esta etapa incluyó la revisión de las variables clave como casos confirmados, muertes, recuperados, y dosis de vacunas administradas, así como la relación de estos indicadores con factores demográficos y de salud pública.

### Principales Insights Obtenidos

- **Tendencias Temporales**:  
   Se observó una clara tendencia decreciente en los casos confirmados y las muertes a lo largo del tiempo, particularmente a partir del segundo trimestre de 2021, lo que coincide con el aumento en la distribución de vacunas.
  
- **Impacto de la Urbanización**:  
   El análisis reveló que los países con mayor porcentaje de población urbana, como Chile, experimentaron una mayor propagación del virus, lo que subraya la importancia de considerar la densidad poblacional y la urbanización en la planificación de la respuesta a la pandemia.
  
- **Relación entre Temperatura y Casos**:  
   La correlación entre el aumento de la temperatura promedio y la disminución de casos sugiere que, aunque la temperatura podría tener algún efecto, las intervenciones como la vacunación son los factores más determinantes en la reducción de casos.
  
- **Distribución Etaria y Mortalidad**:  
   En los países con las tasas de mortalidad más altas, se identificó una mayor concentración de población en grupos etarios vulnerables (mayores de 60 años), lo que podría haber contribuido a las altas tasas de fallecimientos. La prevalencia de comorbilidades, como la diabetes en México y Brasil, y el tabaquismo en Chile y Argentina, fue notablemente alta en estos países, lo que podría explicar en parte las diferencias en la letalidad del virus.
  
- **Estrategias de Vacunación**:  
   Brasil y Colombia mostraron una menor cobertura de vacunación relativa a su población, lo que sugiere la necesidad de reforzar las campañas de vacunación en estos países. Estos hallazgos fueron críticos para determinar los lugares más estratégicos para la expansión de los laboratorios de BIOGENESYS.
  
- **Tasa de Letalidad**:  
   Se observó una reducción reciente en la tasa de letalidad en la mayoría de los países, lo que indica el impacto positivo de las vacunas y otros esfuerzos de mitigación. Sin embargo, Brasil continúa con una tasa de letalidad relativamente alta, lo que lo convierte en un foco prioritario para intervención.

## Análisis del Dashboard

### Página 1: Portada

Portada principal del informe. Esta página sirve como punto de entrada para los usuarios, proporcionando una visión general y facilitando la navegación hacia otras secciones del dashboard.

**Elementos Incluidos**:
- Título de la Empresa
- Botones de Navegación
- Leyenda de Información del Proyecto

### Página 2: Análisis de COVID-19

Análisis detallado de la pandemia de COVID-19, con visualizaciones y datos clave.

**Elementos Incluidos**:
- Tarjetas de Información Clave: Casos de COVID-19, Tasa de Mortalidad, Cantidad de Muertes
- Gráfico de Líneas: Evolución de los casos
- Mapa: Contagiados y Vacunados por País
- Gráfico de Barras: Muertos por País
- Gráfico de Línea: Promedio de Vacunas Administradas
- Segmentadores: Por Fecha y País

### Página 3: Contexto de los Países

Ofrece una visión del contexto demográfico y sanitario de cada país.

**Elementos Incluidos**:
- Tarjetas de Información Demográfica
- Gráfico de Torta: Población Urbana y Rural
- Gráfico de Barras: Rangos Etarios
- Gráfico de Boxplot: Temperaturas Promedio
- Gráfico de Barras Horizontales: Prevalencia de Tabaquismo y Diabetes

## Conclusiones y Recomendaciones

### Conclusiones Estratégicas

- **Políticas de Vacunación**:  
   Brasil y Colombia emergen como los principales candidatos para la expansión de laboratorios farmacéuticos debido a su menor cobertura de vacunación en comparación con la magnitud de sus poblaciones.
  
- **Inversión en Salud**:  
   Invertir en la expansión de laboratorios en países con infraestructuras más débiles pero con alta incidencia de COVID-19, como Perú y Bolivia, podría tener un impacto significativo en la mejora de la atención sanitaria y en la reducción de la mortalidad.
  
- **Densidad Poblacional y Urbanización**:  
   La alta densidad poblacional y el porcentaje elevado de población urbana en países como Chile y Argentina sugieren que las ciudades de estos países serían puntos estratégicos para establecer laboratorios que puedan responder rápidamente a brotes localizados.
  
- **Problemas Sociales y Económicos**:  
   Países con mayores problemas sociales y económicos, como México y Brasil, que además presentan alta prevalencia de comorbilidades como la diabetes y el tabaquismo, requieren una atención especial. La expansión de laboratorios en estas áreas podría facilitar el acceso a tratamientos y mejorar las condiciones de salud de la población vulnerable.
  
- **Respuesta Principal del Proyecto**:  
   Brasil ha sido identificado como la ubicación óptima para la expansión de los laboratorios farmacéuticos de BIOGENESYS.

## Reflexión Personal

Durante este proyecto, he consolidado mis habilidades como Analista de Datos, especialmente en el manejo y visualización de datos para obtener insights clave. Aprendí la importancia de un enfoque meticuloso en la preparación y análisis de datos, lo que permitió identificar patrones críticos para la toma de decisiones estratégicas.

## Extra Credit

En el proyecto, se elaboró un mapa que muestra la distribución de casos confirmados de COVID-19 en varios países de América Latina, incluyendo Argentina, Chile, Colombia, México, Brasil y Perú.
