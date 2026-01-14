# Data-Project-Spotify

La data utilizada en este proyecto fue obtenida a partir de la playlist 
[Top 50: Global](https://open.spotify.com/playlist/37i9dQZEVXbMDoHDwVN2tF) de Spotify, 
y fue extraída mediante la herramienta [Exportify](https://exportify.net/).

Con esta información se desarrolló un **dashboard interactivo en Power BI**, haciendo uso de 
**DAX** para el cálculo de diversas métricas, con un enfoque en el análisis de 
**tendencias musicales**, **artistas** y **sellos discográficos**.

## 🔹 Insights clave
- La popularidad promedio de las canciones del Top 50 es elevada (superior a 90), 
  siendo el Top 10 el que supera ampliamente la media general.
- El **84% de las canciones no presentan contenido explícito**.
- Existe una **alta diversidad de sellos discográficos**, siendo **Columbia** el que cuenta con mayor presencia.
- No se identifica una relación lineal directa entre variables como *tempo* o *danceability* y la popularidad; 
  esta responde a una combinación de múltiples atributos musicales.

La descripción detallada de las columnas utilizadas se encuentra disponible en la documentación oficial de 
[Spotify for Developers – Web API](https://developer.spotify.com/documentation/web-api), 
sección **Tracks**.
