# Establecimientos de juego en el área metropolitana de Valencia

Este repositorio contiene una base de datos geográfica de establecimientos de juego localizados en el área metropolitana de Valencia.

La base se construyó a partir de OpenStreetMap y fue posteriormente enriquecida mediante un proceso de búsqueda y validación manual municipio por municipio.

## Ámbito territorial

El dataset incluye los municipios de la primera y segunda corona metropolitana de Valencia utilizados en el trabajo.

## Fuentes utilizadas

- OpenStreetMap
- Google Maps
- Google Street View
- Páginas web oficiales o presencia digital de los establecimientos cuando estaban disponibles

## Criterios de inclusión

Se incluyeron establecimientos cuya actividad principal está vinculada al juego presencial: salones de juego, casas de apuestas, bingos, casinos y locales equivalentes.

Se excluyeron bares, cafeterías, administraciones de lotería y otros negocios en los que el juego no constituye la actividad principal.

## Proceso de validación

Cada registro fue revisado manualmente. Los establecimientos procedentes de OpenStreetMap fueron contrastados con Google Maps y, cuando fue posible, con Street View o con la página web del local.

Los establecimientos añadidos manualmente fueron localizados mediante búsquedas sistemáticas por municipio y posteriormente revisados uno a uno para comprobar su existencia, ubicación y adecuación a los criterios del estudio.

## Limitaciones

La base no debe interpretarse como un censo administrativo oficial, sino como una reconstrucción abierta, trazable y reutilizable elaborada a partir de fuentes abiertas. Puede contener omisiones o cambios posteriores derivados de aperturas, cierres o modificaciones de los establecimientos.

## Archivos

Este repositorio incluye tres recursos principales:

- **Base de datos en CSV**: archivo tabular con los establecimientos de juego georreferenciados del área metropolitana de Valencia.  
  [Descargar CSV](./establecimientos_juego_valencia_metropolitana.csv)

- **Base de datos en GeoJSON**: versión geográfica del dataset, utilizable en QGIS, ArcGIS, R, Python o visores web.  
  [Descargar GeoJSON](./establecimientos_juego_valencia_metropolitana.geojson)

- **Mapa interactivo**: visualización web de los establecimientos georreferenciados.  
  [Abrir mapa interactivo](./mapa_establecimientos_juego.html)
