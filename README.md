# Metal, felicidad y salud: un análisis mundial

## Descripción del proyecto

Este proyecto analiza la posible relación entre la presencia de bandas de metal en distintos países y dos indicadores sociales: el nivel de felicidad de la población y la esperanza de vida saludable (HALE).

El objetivo es explorar si existe una asociación estadística entre la densidad de bandas de metal por cada 100.000 habitantes, la felicidad y la esperanza de vida saludable, utilizando datos de diferentes fuentes.

## Preguntas de investigación

1.  ¿Existe una relación entre la esperanza de vida saludable y el nivel de felicidad de la población de los distintos países?
2.  ¿Existe una relación entre el número de bandas de metal por cada 100.000 habitantes y el nivel de felicidad de los distintos países?
3.  ¿Existe una relación entre el número de bandas de metal por cada 100.000 habitantes y la esperanza de vida saludable de la población?

## Fuentes de datos

- **Metal Archives:** información sobre bandas de metal, incluyendo país, género y estado de actividad.
- **World Happiness Report:** datos sobre el nivel de felicidad de los distintos países.
- **Banco Mundial:** datos sobre población, utilizados para calcular el número de bandas por cada 100.000 habitantes.
- **Organización Mundial de la Salud (OMS):** datos de esperanza de vida saludable (HALE).

## Metodología

Se realiza una limpieza y transformación de los datos, unificando los países mediante códigos ISO3 para poder combinar las distintas fuentes.

Se calcula la densidad de bandas de metal por cada 100.000 habitantes y se realizan distintos análisis representados en gráficos, mapas y una tabla estadística.

## Estructura del proyecto

- `Projecto_K.Rmd`: documento principal con el código, análisis y resultados.
- `INPUT/Metal/`: datos de Metal Archives.
- `INPUT/Felicidad/`: datos de felicidad.
- `INPUT/Gente/`: datos de población del Banco Mundial.
- `INPUT/HALE/`: datos de esperanza de vida saludable.

## Herramientas

El proyecto se desarrolla en R y R Markdown, utilizando principalmente los paquetes `tidyverse`, `readxl`, `ggplot2`, `sf`, `countrycode` y `rnaturalearth`.
