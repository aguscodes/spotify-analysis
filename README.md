# Proyecto 1: ¿Qué características hacen popular a una canción?

## 📌 Descripción
En este proyecto analizamos con mis compañeros de la materia Introducción a Ciencia de Datos qué factores influyen en la popularidad de las canciones usando un dataset de Kaggle con información sobre características musicales como popularidad, energía y valencia.

## 🔍 Objetivo
Analizar qué variables tienen mayor impacto en la popularidad de una canción y cómo han cambiado a lo largo del tiempo, si es que las hay.

## 📊 Dataset
- **Fuente:** Kaggle
- **Variables clave:**
    - Target: Popularidad.
    - Categóricas:"album name", "artist genre" y "album release date"
    - Numéricas: "Instrumentalness", "Loudness", "Popularity", "valence", "danceability", "energy", "track duration"
## 🛠️ Metodología
1. **Limpieza y tratamiento de datos:**
  - Descartamos categorías con alta cantidad de valores faltables
  - modificamos la categoría "género" para que cada género sea una categoría
  - elegimos los 5 géneros más escuchados y descartamos los demás
  - descartamos las canciones con popularidad "0"
  - clasificamos las características musicales en 3 categorías en base a su distribución
3. **Análisis exploratorio:** No identificamos ningún tipo de patrón en relación a ningún género o carácteristica. Era distinto en cada una de ellas
4. **Modelo predictivo:** Implementación de regresión lineal simple para evaluar la relación entre variables y popularidad.

## 🔎 Principales hallazgos
- Las canciones tristes y bailables son las que mantienen más popularidad a través de las décadas.
- No hubo una única variable dominante, por lo que se consideraron todas en el análisis.
- Se observó un cambio en las tendencias musicales en cuanto a géneros a lo largo de los años.

## 🛠️ Tecnologías utilizadas
- R (tidyr,

## 📂 Archivos
- `canciones_populares.ipynb`: Código del análisis.
- https://www.kaggle.com/datasets/joebeachcapital/top-10000-spotify-songs-1960-now/data
- `presentación.pdf`: Resumen visual del análisis (opcional).

## 🚀 Cómo usar este repositorio
1. Clonar el repositorio:  
   ```bash
   git clone https://github.com/tu_usuario/canciones-populares.git
   ```
2. Abrir el Jupyter Notebook y ejecutar las celdas.
