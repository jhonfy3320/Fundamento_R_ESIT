# Fundamento_R_ESIT
# Introducción al lenguaje de R para Data Scientist
# Análisis de Datos: Economía Naranja en LATAM

Este repositorio contiene un proyecto de análisis de datos aplicado a la Economía Naranja en países de América Latina, utilizando herramientas como R y paquetes como `ggplot2`, `dplyr` y `plotly`. Aquí exploramos las relaciones entre variables clave como penetración de Internet, PIB per cápita, y contribución de la economía creativa al PIB.

## Contenido

- `economia-naranja.Rmd`: Script en R Markdown que realiza el análisis y genera reportes en formatos reproducibles (PDF, HTML).
- `orangeec.csv`: Dataset utilizado para el análisis.
- Gráficos y visualizaciones: Exploración visual de las variables y relaciones clave.
- `scripts/`: Scripts adicionales usados para limpieza y transformación de datos.

## Herramientas Utilizadas

- **Lenguaje**: R
- **Paquetes**:
  - `ggplot2` para visualización de datos
  - `dplyr` para manipulación de datos
  - `plotly` para visualizaciones interactivas
  - `knitr` y `rmarkdown` para generación de reportes reproducibles
- **Software**: RStudio

## Estructura del Proyecto

1. **Exploración de Datos (EDA)**:
   - Visualización de la distribución de datos usando histogramas y box plots.
   - Identificación de correlaciones entre variables clave con `pairs()` y `cor()`.

2. **Transformación de Datos**:
   - Eliminación de valores faltantes (NA's).
   - Creación de nuevas variables, como categorías de eficiencia y métricas relevantes.

3. **Visualizaciones Interactivas**:
   - Gráficos de dispersión con múltiples variables (facetas por país).
   - Uso de `plotly` para enriquecer la interacción en los gráficos.

4. **Reporte Reproducible**:
   - Documento en PDF que organiza y presenta los hallazgos del análisis.

## Cómo Usar Este Repositorio

### Requisitos Previos
1. Instalar R y RStudio.
2. Instalar los paquetes necesarios ejecutando:
   ```r
   install.packages(c("ggplot2", "dplyr", "plotly", "knitr", "rmarkdown"))
