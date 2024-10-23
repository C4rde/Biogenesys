**Análisis para la Expansión de Laboratorios en América Latina**

**Nombre del autor:** Ignacio Cardetti

**Email:** nachocardetti1@gmail.com

**Cohorte:** DA-FT05

**Fecha de entrega:** 23/08/2024

**Institución**: *BIOGENESYS* 

**![][image1]**

**Índice:**

**[Introducción	3](#introducción)**

[**Desarrollo del proyecto	3**](#desarrollo-del-proyecto)

[Importación y Preparación de Datos:	3](#importación-y-preparación-de-datos:)

[Análisis del Comportamiento de la Pandemia:	3](#análisis-del-comportamiento-de-la-pandemia:)

[Impacto de la Temperatura:	3](#impacto-de-la-temperatura:)

[Urbanización y Densidad Poblacional:	3](#urbanización-y-densidad-poblacional:)

[Estrategias de Vacunación:	4](#estrategias-de-vacunación:)

[Condiciones Preexistentes:	4](#condiciones-preexistentes:)

[Tasa de Letalidad y Reducción de Casos:	4](#tasa-de-letalidad-y-reducción-de-casos:)

[Situación Actual:	4](#situación-actual:)

[**EDA e insights	4**](#eda-e-insights)

[Exploración de Datos Inicial (EDA):	4](#exploración-de-datos-inicial-\(eda\):)

[Principales Insights Obtenidos:	5](#principales-insights-obtenidos:)

[★ Tendencias Temporales:	5](#tendencias-temporales:)

[★ Impacto de la Urbanización:	5](#impacto-de-la-urbanización:)

[★ Relación entre Temperatura y Casos:	5](#relación-entre-temperatura-y-casos:)

[★ Distribución Etaria y Mortalidad:	5](#distribución-etaria-y-mortalidad:)

[★ Estrategias de Vacunación:	5](#estrategias-de-vacunación:-1)

[★ Tasa de Letalidad:	5](#tasa-de-letalidad:)

[**Análisis del dashboard	6**](#análisis-del-dashboard)

[Página 1: Portada	6](#página-1:-portada)

[Página 2: Análisis de COVID-19	6](#página-2:-análisis-de-covid-19)

[Página 3: Contexto de los Países	7](#página-3:-contexto-de-los-países)

[**Conclusiones y Recomendaciones	8**](#conclusiones-y-recomendaciones)

[Conclusiones Estratégicas:	8](#conclusiones-estratégicas:)

[★ Inversión en Salud:	8](#inversión-en-salud:)

[★ Densidad Poblacional y Urbanización:	8](#densidad-poblacional-y-urbanización:)

[★ Problemas Sociales y Económicos:	8](#problemas-sociales-y-económicos:)

[★ Respuesta Principal del Proyecto:	9](#respuesta-principal-del-proyecto:)

[**Reflexión personal	9**](#reflexión-personal)

[**EXTRA CREDIT	9**](#extra-credit)

# **Introducción** {#introducción}

	*BIOGENESYS* es una empresa del rubro farmacéutico que busca identificar las ubicaciones óptimas para la expansión de laboratorios farmacéuticos, basándose en el análisis de datos de incidencia de COVID-19, tasas de vacunación, y la disponibilidad de infraestructuras sanitarias. La meta es optimizar la respuesta a los efectos de la pandemia y post pandemia con el fin de mejorar el acceso a las vacunas.

# **Desarrollo del proyecto** {#desarrollo-del-proyecto}

## Importación y Preparación de Datos: {#importación-y-preparación-de-datos:}

 Se trabajó con un conjunto de datos que incluía información sobre la evolución de la pandemia en diversos países latinoamericanos. Estos datos se prepararon cuidadosamente para asegurar su integridad, lo que incluyó la eliminación de valores nulos y anómalos, y la transformación de las variables para su posterior análisis.

## Análisis del Comportamiento de la Pandemia:  {#análisis-del-comportamiento-de-la-pandemia:}

El análisis se enfocó en el comportamiento de los casos de COVID-19 a lo largo del tiempo, tanto de forma semanal como anual. Este análisis reveló una tendencia general a la disminución de casos y muertes conforme avanzaba el tiempo, lo que sugiere que las estrategias de control y vacunación han sido efectivas en la región.

## Impacto de la Temperatura:  {#impacto-de-la-temperatura:}

Se investigó la relación entre la temperatura promedio y la evolución de los casos de COVID-19. Se observó que, aunque la temperatura ha ido en aumento, los casos han disminuido, especialmente después de picos notables antes de marzo, lo que podría estar vinculado a la efectividad de las campañas de vacunación.

## Urbanización y Densidad Poblacional:  {#urbanización-y-densidad-poblacional:}

Se analizó el impacto de la urbanización y la densidad poblacional en la propagación del virus. Chile, con un alto porcentaje de población urbana, mostró una mayor propagación del virus. Este análisis también incluyó la distribución de la población por grupos etarios en países con altas tasas de mortalidad, lo que ayudó a identificar a los grupos más vulnerables.

## Estrategias de Vacunación:  {#estrategias-de-vacunación:}

Las estrategias de vacunación se compararon entre los países, revelando que Brasil y Colombia son los que más podrían beneficiarse de una intervención debido a su baja tasa de vacunación en relación con su población. Estos hallazgos sugieren que la expansión de los laboratorios en estos países podría tener un impacto significativo en la lucha contra la pandemia.

## Condiciones Preexistentes:  {#condiciones-preexistentes:}

Se estudió la prevalencia de condiciones de salud preexistentes, como la diabetes y el tabaquismo, en los países con las tasas de mortalidad más altas. Se descubrió que México y Brasil tienen una alta prevalencia de diabetes, mientras que Chile y Argentina presentan mayores tasas de tabaquismo, lo que podría haber contribuido a las altas tasas de mortalidad en estos países.

## Tasa de Letalidad y Reducción de Casos:  {#tasa-de-letalidad-y-reducción-de-casos:}

Se calculó la tasa de letalidad del COVID-19 en cada país, lo que mostró una disminución en la letalidad reciente, posiblemente debido a la efectividad de las vacunas. Además, se analizó la evolución de los casos activos y recuperados, demostrando que los casos activos han disminuido mientras que los recuperados han aumentado, lo que refuerza la importancia de la vacunación.

## Situación Actual:  {#situación-actual:}

El análisis concluyó con una comparación de la situación actual de los países seleccionados, teniendo en cuenta los casos activos, recuperados y fallecidos. Brasil emergió como el país prioritario para la expansión, debido a su alta cantidad de casos confirmados y muertes, así como a su relativamente baja tasa de vacunación.

# **EDA e insights** {#eda-e-insights}

## Exploración de Datos Inicial (EDA):  {#exploración-de-datos-inicial-(eda):}

Para comprender mejor la naturaleza y el comportamiento de los datos relacionados con la pandemia de COVID-19 en América Latina, se realizó un análisis exploratorio exhaustivo. Esta etapa incluyó la revisión de las variables clave como casos confirmados, muertes, recuperados, y dosis de vacunas administradas, así como la relación de estos indicadores con factores demográficos y de salud pública.

## Principales Insights Obtenidos: {#principales-insights-obtenidos:}

* ### **Tendencias Temporales:** {#tendencias-temporales:}

  * Se observó una clara tendencia decreciente en los casos confirmados y las muertes a lo largo del tiempo, particularmente a partir del segundo trimestre de 2021, lo que coincide con el aumento en la distribución de vacunas.  
  * Los picos significativos en el número de casos antes de marzo de 2021 fueron seguidos por descensos pronunciados, lo que sugiere un impacto positivo de las medidas de vacunación y las políticas de salud pública.

* ### **Impacto de la Urbanización:** {#impacto-de-la-urbanización:}

  * El análisis reveló que los países con mayor porcentaje de población urbana, como Chile, experimentaron una mayor propagación del virus, lo que subraya la importancia de considerar la densidad poblacional y la urbanización en la planificación de la respuesta a la pandemia.

* ### **Relación entre Temperatura y Casos:** {#relación-entre-temperatura-y-casos:}

  * La correlación entre el aumento de la temperatura promedio y la disminución de casos sugiere que, aunque la temperatura podría tener algún efecto, las intervenciones como la vacunación son los factores más determinantes en la reducción de casos.

* ### **Distribución Etaria y Mortalidad:** {#distribución-etaria-y-mortalidad:}

  * En los países con las tasas de mortalidad más altas, se identificó una mayor concentración de población en grupos etarios vulnerables (mayores de 60 años), lo que podría haber contribuido a las altas tasas de fallecimientos.  
  * La prevalencia de comorbilidades, como la diabetes en México y Brasil, y el tabaquismo en Chile y Argentina, fue notablemente alta en estos países, lo que podría explicar en parte las diferencias en la letalidad del virus.

* ### **Estrategias de Vacunación:** {#estrategias-de-vacunación:-1}

  * Brasil y Colombia mostraron una menor cobertura de vacunación relativa a su población, lo que sugiere la necesidad de reforzar las campañas de vacunación en estos países. Estos hallazgos fueron críticos para determinar los lugares más estratégicos para la expansión de los laboratorios de BIOGENESYS.

* ### **Tasa de Letalidad:** {#tasa-de-letalidad:}

  * Se observó una reducción reciente en la tasa de letalidad en la mayoría de los países, lo que indica el impacto positivo de las vacunas y otros esfuerzos de mitigación. Sin embargo, Brasil continúa con una tasa de letalidad relativamente alta, lo que lo convierte en un foco prioritario para intervención.

# 

# **Análisis del dashboard** {#análisis-del-dashboard}

## Página 1: Portada {#página-1:-portada}

Portada principal del informe. Esta página sirve como punto de entrada para los usuarios, proporcionando una visión general y facilitando la navegación hacia otras secciones del dashboard.

Elementos Incluidos:

* **Título de la Empresa**  
* **Botones de Navegación:**  
  * Los botones están diseñados para redirigir a los usuarios a las diferentes páginas del dashboard.  
* **Leyenda de Información del Proyecto**  
  * Proporciona información clave sobre el proyecto y el creador del dashboard, así como la versión actual del informe, lo cual es importante para la identificación y seguimiento de versiones.

## Página 2: Análisis de COVID-19 {#página-2:-análisis-de-covid-19}

Análisis detallado de la pandemia de COVID-19. Presenta una serie de visualizaciones y tarjetas que proporcionan información clave sobre los casos, las muertes, y las vacunas administradas, facilitando la comprensión de la evolución de la pandemia a nivel global y regional.

Elementos Incluidos:

* **Tarjetas de Información Clave:**  
  * Casos de COVID-19:  
    * Muestra el número total de casos confirmados de COVID-19.  
  * Tasa de Mortalidad:  
    * Indica el porcentaje de muertes en relación con el número total de casos.  
  * Cantidad de Muertes:  
    * Número total de muertes atribuibles a COVID-19.  
* **Gráfico de Líneas \- Contagios a Través del Tiempo:**  
  * Representa la evolución de los casos de COVID-19 a lo largo del tiempo, permitiendo observar tendencias y fluctuaciones.  
* **Mapa \- Contagiados y Vacunados por País:**  
  * Muestra un mapa interactivo que visualiza la distribución geográfica de los casos confirmados y el número de vacunas administradas por país.  
* **Gráfico de Barras \- Muertos por País:**  
  * Presenta un gráfico de barras que compara el número de muertes por país, facilitando la comparación entre regiones.  
* **Gráfico de Línea \- Promedio de Vacunas Administradas por Año y Mes:**  
  * Representa el promedio mensual y anual de vacunas administradas, permitiendo observar la evolución en el tiempo.  
* **Segmentadores:**  
  * Por Fecha:  
    * Permite filtrar los datos mostrados en la página según diferentes periodos de tiempo.  
  * Por País:  
    * Facilita la selección de países específicos para analizar los datos relacionados.

## Página 3: Contexto de los Países {#página-3:-contexto-de-los-países}

Análisis detallado sobre aspectos demográficos y de salud de los países que no están directamente relacionados con COVID-19. Esta página ofrece una visión más amplia del contexto general de cada país, ayudando a entender mejor las condiciones locales.

Elementos Incluidos:

* **Tarjetas de Información Demográfica:**  
  * Cantidad de Población:  
    * Muestra el número total de habitantes en cada país.  
  * Densidad Poblacional:  
    * Indica el número de personas por unidad de área en cada país, proporcionando una visión de cuán concentrada está la población.  
* **Gráfico de Torta \- Población Urbana y Rural:**  
  * Representa la proporción de población urbana frente a rural en cada país, permitiendo observar la distribución geográfica de la población.  
* **Gráfico de Barras \- Rangos Etarios:**  
  * Muestra la distribución de la población en diferentes rangos etarios, proporcionando información sobre la estructura demográfica.  
* **Gráfico de Boxplot \- Temperaturas Promedio de los Países:**  
  * Representa la variabilidad y la distribución de las temperaturas promedio en cada país, ayudando a entender las condiciones climáticas.  
* **Gráfico de Barras Horizontales \- Prevalencia de Tabaquismo y Diabetes:**  
  * Muestra la prevalencia de tabaquismo y diabetes en diferentes países, permitiendo comparar la salud pública.  
* **Segmentadores:**  
  * Por Fecha:  
    * Permite filtrar los datos mostrados en la página según diferentes periodos de tiempo.  
  * Por País:  
    * Facilita la selección de países específicos para analizar los datos relacionados.

# **Conclusiones y Recomendaciones** {#conclusiones-y-recomendaciones}

A lo largo del análisis realizado, se obtuvieron valiosos insights sobre la evolución del COVID-19 en América Latina y su impacto en distintos países. A partir de las visualizaciones y del dashboard desarrollado, se observó una disminución general de los casos y muertes a medida que avanzaban las campañas de vacunación. Sin embargo, esta tendencia no fue homogénea en toda la región, ya que factores como la densidad poblacional, la urbanización, la prevalencia de enfermedades preexistentes y las políticas de salud pública influyeron significativamente en los resultados observados.

El análisis confirmó que Brasil, a pesar de tener la mayor cantidad de dosis de vacunas administradas, sigue enfrentando altos números de casos confirmados y muertes. Además, se identificó que la cobertura de vacunación en relación con su población es menor en comparación con otros países, lo que lo convierte en un país prioritario para la expansión de los laboratorios farmacéuticos de BIOGENESYS.

## Conclusiones Estratégicas: {#conclusiones-estratégicas:}

* **Políticas de Vacunación:**  
  * Brasil y Colombia emergen como los principales candidatos para la expansión de laboratorios farmacéuticos debido a su menor cobertura de vacunación en comparación con la magnitud de sus poblaciones. Estos países requieren un refuerzo en sus campañas de vacunación para aumentar la inmunización y controlar mejor la propagación del virus.

* ### Inversión en Salud: {#inversión-en-salud:}

  * La infraestructura sanitaria y la capacidad de respuesta de los sistemas de salud varían considerablemente entre los países analizados. Invertir en la expansión de laboratorios en países con infraestructuras más débiles pero con alta incidencia de COVID-19, como Perú y Bolivia, podría tener un impacto significativo en la mejora de la atención sanitaria y en la reducción de la mortalidad.

* ### Densidad Poblacional y Urbanización: {#densidad-poblacional-y-urbanización:}

  * La alta densidad poblacional y el porcentaje elevado de población urbana en países como Chile y Argentina sugieren que las ciudades de estos países serían puntos estratégicos para establecer laboratorios que puedan responder rápidamente a brotes localizados, especialmente en áreas densamente pobladas.

* ### Problemas Sociales y Económicos: {#problemas-sociales-y-económicos:}

  * Países con mayores problemas sociales y económicos, como México y Brasil, que además presentan alta prevalencia de comorbilidades como la diabetes y el tabaquismo, requieren una atención especial. La expansión de laboratorios en estas áreas podría facilitar el acceso a tratamientos y mejorar las condiciones de salud de la población vulnerable.

* ### Respuesta Principal del Proyecto: {#respuesta-principal-del-proyecto:}

  * Brasil ha sido identificado como la ubicación óptima para la expansión de los laboratorios farmacéuticos de BIOGENESYS. Este país presenta la combinación más crítica de alta incidencia de casos confirmados y muertes, junto con una menor cobertura de vacunación. La expansión en Brasil permitirá una intervención más efectiva en la mejora del acceso a vacunas y tratamientos, particularmente en las regiones más afectadas.

**Resumen Final:**

El análisis integral realizado en este proyecto permitió identificar las áreas prioritarias para la expansión de los laboratorios de BIOGENESYS, basándose en datos de salud, demografía y respuesta a la pandemia en América Latina. La implementación de estas estrategias fortalecerá la capacidad de respuesta ante futuras emergencias sanitarias y mejorará la salud pública en las regiones más necesitadas.

# **Reflexión personal** {#reflexión-personal}

Durante este proyecto, he consolidado mis habilidades como Analista de Datos, especialmente en el manejo y visualización de datos para obtener insights clave. Aprendí la importancia de un enfoque meticuloso en la preparación y análisis de datos, lo que permitió identificar patrones críticos para la toma de decisiones estratégicas.

Si tuviera que empezar de nuevo, mantendría el enfoque general del proyecto, pero buscaría optimizar ciertos procesos, como la recolección de datos y su limpieza inicial, para asegurar una mayor precisión desde el principio. Además, podría explorar la incorporación de más variables contextuales, como factores económicos y políticos, para enriquecer el análisis y ofrecer una visión más completa.

# **EXTRA CREDIT** {#extra-credit}

En el proyecto, como parte del análisis adicional, se elaboró un mapa que muestra la distribución de casos confirmados de COVID-19 en varios países de América Latina, incluyendo Argentina, Chile, Colombia, México, Brasil y Perú. Este mapa proporciona una visualización clara de la concentración de casos en la región, permitiendo identificar de manera geoespacial las áreas más afectadas. La inclusión de este mapa en el informe añade valor al análisis al ofrecer una perspectiva visual y geográfica de la propagación del virus en los países seleccionados.

<<<<<<< HEAD
[image1]: <data:image/png;base64,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>
=======
[image1]: <data:image/png;base64,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>
>>>>>>> 1f5b7351605ef4be41bba62333ad4a3d9cbca39c
>>>>>>> d49c8b4a2e67452eb62ea6d170dfae04ef33a920
