## Análisis de popularisdad de canciones

Este proyecto lo desarrollé con mis compañeros de la materia Introducción a Ciencia de Datos, hicimos un analisis de la distribución de ciertas características musicales y como estas influyen en la popularidad de las canciones. Usamos un dataset en kaggle usando un dataset de Kaggle con información sobre características musicales como popularidad, energía y valencia. - https://www.kaggle.com/datasets/joebeachcapital/top-10000-spotify-songs-1960-now/data

## Objetivo
Nuesro objetivo fue tratar de encontrar alguna relación entre las variables y la popularidad de las canciones, si su distribución cambiaba a lo largo de las décadas. Usamos R  como herramienta, pricipalmente la libreria tidyr
    - Target: Popularidad.
    - Categóricas:"album name", "artist genre" y "album release date"
    - Numéricas: "Instrumentalness", "Loudness", "Popularity", "valence", "danceability", "energy", "track duration"
    
1. **Limpieza y tratamiento de datos:**
  - Descartamos categorías con alta cantidad de valores faltables
  - modificamos la categoría "género" para que cada género sea una categoría
  - elegimos los 5 géneros más escuchados y descartamos los demás
  - descartamos las canciones con popularidad "0"
  - clasificamos las características musicales en 3 categorías en base a su distribución
3. **Análisis exploratorio:** No identificamos ningún tipo de patrón en relación a ningún género o carácteristica. Era distinto en cada una de ellas
4. **Modelo predictivo:** Implementamos regresión lineal simple para evaluar la relación entre variables y popularidad.

## Conclusiones finales
- Las canciones tristes y bailables son las que mantienen más popularidad a través de las décadas.
- No hubo una única variable dominante, por lo que se consideraron todas en el análisis.
- Se observó un cambio en las tendencias musicales en cuanto a géneros a lo largo de los años.

