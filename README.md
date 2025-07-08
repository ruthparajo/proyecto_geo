# Reintroducción de Lobos: Cambios en Yellowstone

Ruth Parajó
Benjamín Muñóz
Claudia Rodríguez

En este repositorio se encuentran los siguientes archivos:
- `analisis_ndvi.ipynb`: Consiste en la visualización del parque Yellowstone y el NDVI. Contiene la creación de un GIF del NDVI a lo largo del tiempo y un ajuste lineal al NDVI promedio en el tiempo.
- `clustering.ipynb`: Contiene el clustering para los dos períodos mencionados en el informe utilizando los datos preprocesados. Se utilizan los territorios de lobos, el NDVI, el NLCD, y los territorios de lobos.
- `moran.ipynb`: Contiene el análisis de autocorrelaciones involucrando variables como el NDVI, y el tipo de uso de suelo.
- `preprocessing.ipynb`: Contiene el procesamiento de los datos, lo que incluye la conversión de la región de interés en una grilla más trabajable y también la reproyección de algunos archivos como el NDVI y LST.
- `territorio_lobos.ipynb`: Trabaja con los polígonos de los territorios de lobos. Consiste en construir GeoDataFrames para cada año con todos los territorios involucrados. Se busca el área de territorios por cada año. Se construye un gif de la evolución de territorio por año.

Links de fuentes de datos:
- Yellowstone boundary: https://catalog.data.gov/dataset/yellowstone-national-park-tract-and-boundary-data
- Water bodies USA: https://hub.arcgis.com/datasets/esri::usa-detailed-water-bodies/explore?location=29.254113%2C-113.614487%2C4.59
- Uso de suelo: https://www.mrlc.gov/viewer/ 

    - 2001, 2011: https://developers.google.com/earth-engine/datasets/catalog/USGS_NLCD_RELEASES_2019_REL_NLCD?hl=es-419 
    - 2021: https://developers.google.com/earth-engine/datasets/catalog/USGS_NLCD_RELEASES_2021_REL_NLCD?hl=es-419 

- Rutas de migraciones de ciervos entre 2004-2019: https://www.sciencebase.gov/catalog/item/5f80c88d82cebef40f0fefc5, 
    - Publicación del survey: https://pubs.usgs.gov/sir/2020/5101/sir20205101.pdf

- Territorios de lobos: https://www.nps.gov/yell/learn/nature/wolf-reports.htm de 1995 hasta 2022.

Datos:

- `1996_2022-YELL-wolf-data`: Contiene los polígonos de los territorios.
- `imagenes_dinamicas`: Contiene los gifs de NDVI y territorio en el tiempo.
- `lst`: Contiene los raster de LST de los dos períodos estudiados.
- `ncld`: Contiene la información del tipo de uso de suelo.
- `ndvi_frames`: Contiene una imagen del NDVI de cada año estudiado.
- `ndvi_mndwi`: Contiene los raster del NDVI y MNDWI.
- `territorio_frames`: Contiene una imagen de los territorios de cada año estudiado.
- `YELL_tracts`: El polígono de Yellowstone.