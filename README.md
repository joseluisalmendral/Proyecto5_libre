# Proyecto de Investigación: Análisis del Mercado Laboral en el Mundo del Data

## Descripción General

Este proyecto tiene como objetivo realizar una investigación en profundidad sobre el mercado laboral en el campo de los datos (Data Science, Data Engineering, Machine Learning, entre otros). Para ello, se está desarrollando un sistema de scraping que recopilará ofertas de trabajo de diversas plataformas, incluyendo **LinkedIn**, **InfoJobs** y otros sitios de empleo relevantes. Estos datos permitirán analizar tendencias, habilidades demandadas y otros aspectos clave de las oportunidades laborales en el sector.

**Nota**: Este proyecto se encuentra en una fase inicial y actualmente no está completo. La configuración del entorno, la recolección de datos y la integración de fuentes aún están en progreso.

## Objetivos del Proyecto

1. **Scraping de Múltiples Sitios Web**: Recopilar ofertas de empleo relacionadas con el ámbito de los datos desde plataformas de empleo, principalmente LinkedIn e InfoJobs. Esto permitirá construir un dataset amplio y enriquecido de oportunidades laborales en el sector.

2. **Integración de APIs Adicionales**: Utilizar al menos dos APIs que complementen los datos recopilados mediante scraping. Estas APIs pueden aportar información adicional sobre tendencias laborales, habilidades en demanda, o salarios promedios en el sector.

3. **Almacenamiento en Base de Datos**: Organizar y almacenar los datos recopilados en una base de datos SQL para facilitar el análisis y la consulta de información. Si el análisis incluye datos geoespaciales, se podría considerar el uso de MongoDB para optimizar consultas específicas.

4. **Visualización y Análisis**: Desarrollar visualizaciones y análisis exploratorio utilizando Python para identificar patrones relevantes en las ofertas de trabajo, como las habilidades más demandadas, los rangos salariales, y las tendencias de contratación en distintas ubicaciones.

## Metodología

### 1. Scraping Web

El proyecto utilizará técnicas de scraping para extraer datos de al menos dos plataformas de empleo. Esto se hará respetando los términos y condiciones de cada sitio web y utilizando herramientas como `BeautifulSoup` o `Selenium` para la recolección automatizada de datos.

### 2. APIs Complementarias

Se seleccionarán e integrarán al menos dos APIs que aporten datos adicionales y complementen la información obtenida mediante scraping. Por ejemplo, se podría utilizar una API que ofrezca información de habilidades en demanda o datos salariales actualizados.

### 3. Estructuración en Base de Datos

Todos los datos serán estructurados y almacenados en una base de datos SQL para su fácil acceso y consulta. En caso de que se incluyan datos geoespaciales, se considerará MongoDB como alternativa para optimizar consultas de este tipo.

### 4. Análisis Visual y Exploratorio

Se utilizarán bibliotecas de visualización en Python, como `matplotlib` y `seaborn`, para comunicar los hallazgos clave. Estas visualizaciones ayudarán a responder preguntas importantes como:

- ¿Cuáles son las habilidades y tecnologías más demandadas en el ámbito de los datos?
- ¿Qué rangos salariales se ofrecen según el nivel de experiencia?
- ¿Cuáles son las principales ubicaciones para estos empleos?

## Estado Actual del Proyecto

Actualmente, este proyecto **no está terminado** y se encuentra en una fase preliminar. Las siguientes actividades están en progreso:

- Configuración del entorno de scraping y selección de las plataformas a incluir.
- Investigación y selección de APIs adicionales para enriquecer el análisis.
- Desarrollo de la estructura de la base de datos para el almacenamiento de los datos.
- Definición de las visualizaciones y análisis a realizar una vez recopilados los datos.

## Próximos Pasos

1. Completar la fase de scraping y recolección de datos desde LinkedIn e InfoJobs.
2. Integrar las APIs seleccionadas para obtener datos adicionales.
3. Estructurar y almacenar los datos en la base de datos seleccionada.
4. Realizar el análisis exploratorio y construir visualizaciones que revelen patrones y tendencias en el mercado laboral.


