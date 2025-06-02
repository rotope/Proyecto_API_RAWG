# Análisis de Datos de Videojuegos con la API RAWG 🎮

Este proyecto tiene como objetivo extraer, transformar y analizar datos de videojuegos utilizando la API pública de RAWG. Se abordan distintas preguntas clave relacionadas con la popularidad, puntuación y plataformas de los videojuegos. El análisis ha sido desarrollado como parte de una iniciativa formativa con fines académicos y profesionales.

## 📁 Estructura del Proyecto

El proyecto se divide en tres etapas principales, cada una representada por un notebook Jupyter:

### 1. Extracción de Datos – [`1_extraccion_datos_rawg.ipynb`](notebooks/1_extraccion_datos_rawg.ipynb)
En este notebook se realiza la conexión con la API RAWG para recolectar datos relevantes de videojuegos publicados entre 2015 y 2024. La información extraída incluye:
- Nombre del videojuego
- Géneros asociados
- Fecha de lanzamiento
- Valoración media (rating)
- Tiempo de juego (playtime)
- Número de veces añadido por los usuarios (`added`)
- Plataformas disponibles

Se realizan múltiples peticiones paginadas para garantizar una cobertura completa de los datos por año.

### 2. Limpieza y Transformación de Datos – [`2_limpieza_datos_rawg.ipynb`](notebooks/2_limpieza_datos_rawg.ipynb)
En esta etapa se lleva a cabo la preparación del dataset para su análisis:
- Normalización de columnas anidadas (como los géneros o plataformas)
- Tratamiento de valores nulos
- Conversión de formatos y filtrado de información irrelevante
- División por rangos de años para comparativas (2015–2019 y 2020–2024)
- Generación de nuevas columnas auxiliares para análisis (e.g. `genero_principal`, `added_clean`, etc.)

### 3. Análisis, Visualización de Datos y Conclusiones – [`3_analisis_conclusiones.ipynb`](notebooks/3_analisis_conclusiones.ipynb)
Este notebook presenta el análisis visual y estadístico de los datos. Cada integrante del grupo ha desarrollado una línea de investigación distinta:

---

## 🎯 Objetivos del Análisis

### 📌 Pedro Rodríguez Tornero
**Pregunta:** ¿Qué géneros de videojuegos han sido más populares cada año?

- Análisis por cantidad de videojuegos y por número de añadidos (`added`)
- Clasificación y visualización por rangos de años (Top 5 y Top 10 de géneros)
- Correlación entre popularidad y valores como `added` y `playtime`

### 📌 Alejandro Guerra
**Pregunta:** ¿Qué relación existe entre la popularidad y la puntuación de un videojuego?

- Cálculo de correlaciones entre las métricas `rating` y `added`
- Análisis visual con gráficos de dispersión y heatmaps
- Discusión sobre el equilibrio entre éxito comercial y valoración crítica

### 📌 Alejandro Cambón Sánchez
**Pregunta:** ¿Qué plataformas tienen mejores valoraciones promedio de juegos?

- Agrupación de datos por plataformas
- Media de puntuaciones (`rating`) por cada sistema
- Visualización comparativa entre consolas y PC

### 📌 Ignacio Buhigas León
**Pregunta:** ¿Cómo ha evolucionado la puntuación media de los videojuegos con los años?

- Tendencia temporal de las valoraciones desde 2015
- Cálculo de medias anuales y regresiones lineales
- Discusión sobre cambios en la percepción de calidad a lo largo del tiempo

---

## 👨‍💻 Participantes

- **Pedro Rodríguez Tornero** – [LinkedIn](https://www.linkedin.com/in/pedro-rodr%C3%ADguez-tornero-a21520270/)
- **Alejandro Guerra** – [LinkedIn](https://www.linkedin.com/in/alejandro-guerra-herrera-a86053115/)
- **Alejandro Cambón Sánchez** – [LinkedIn](https://www.linkedin.com/in/alejandro-cambón-sánchez-5322342b8/)
- **Ignacio Buhigas León** – [LinkedIn](https://www.linkedin.com/in/ignaciobuhigas/)

---

## 🧠 Tecnologías Utilizadas

- Python
- Pandas
- Matplotlib & Seaborn
- API RAWG (https://rawg.io/apidocs)
- Jupyter Notebooks
- Git & GitHub

---

## 📌 Notas Finales

Este repositorio está pensado como una herramienta de presentación profesional. Todos los análisis y visualizaciones han sido realizados con código reproducible, estructurado y documentado.

