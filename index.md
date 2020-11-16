## Índice
{: .no_toc .text-delta }
* TOC
{:toc}

## Detalles del curso
{:toc}
- **Nivel:** Básico (No se requiere conocimientos previos)
- **Lugar:** Se realizará de modo virtual mediante Google Meet.
- **Fecha:** 16 de noviembre de 2020
- **Hora:** El curso está programado para una duración de 4 horas pero al ser virtual su duración puede verse reducido.

## Instalación de QGIS
{:toc}
Este curso introductorio se realizará sobre la versión de largo plazo "A Coruña" ya que tienen una mayor estabilidad. Si alguno prefiere instalar una versión más actual no habrá problema para poder seguir los contenidos.

QGIS es un software SIG de escritorio gratuito y libre por lo que podéis descargar el programa desde su web oficial

[https://www.qgis.org/es/site/forusers/download.html](https://www.qgis.org/es/site/forusers/download.html)

- [Instalador Windows](https://qgis.org/downloads/QGIS-OSGeo4W-3.10.11-2-Setup-x86_64.exe)
- [Instalador macOS](https://qgis.org/downloads/macos/qgis-macos-ltr.dmg)
- Instalador Linux: Accede a la web de descargas para instalar según tu distro

## Obejtivos del curso
{:toc}
- Dar a conocer QGIS como alternativa al software SIG propietario
-	Mostrar las diferentes partes de la interfaz y su funcionalidad
-	Mostrar diferentes herramientas básicas
-	Mostrar el flujo de trabajo completo con QGIS para la creación de un mapa
-	Mostrar diferentes complementos útiles para la adquisición, manipulación, visualización y exportación de datos

## Destinatarios
{:toc}
El curso está enfocado y destinado a toda la comunidad universitaria (Personal Docente Investigador y alumnado).

## Contenido del curso
{:toc}

###	Presentación de QGIS
###	Introducción a la interfaz y funciones básicas
###	Importar diferentes formatos de datos espaciales

XYZ Tiles (Cuidado con el tipo de licencia):
- OpenStreetMap: http://a.tile.openstreetmap.org/{z}/{x}/{y}.png
- [OpenStreetMap Mapnick](http://tile.openstreetmap.org/{z}/{x}/{y}.png)
- OSM Cycle Map: (http://tile.thunderforest.com/cycle/{z}/{x}/{y}.png)
- OSM Black and White: (http://tiles.wmflabs.org/bw-mapnik/{z}/{x}/{y}.png)
- OSM2World/3D (D,A,CH): (http://tiles.osm2world.org/osm/pngtiles/n/{z}/{x}/{y}.png)
- Google Maps: (https://mt1.google.com/vt/lyrs=r&x={x}&y={y}&z={z})
- Google Satellite: (http://www.google.cn/maps/vt?lyrs=s@189&gl=cn&x={x}&y={y}&z={z})
- Google Hybrid: (https://mt1.google.com/vt/lyrs=y&x={x}&y={y}&z={z})
- Google Terrain: (https://mt1.google.com/vt/lyrs=t&x={x}&y={y}&z={z})
- Google Traffic: (https://mt1.google.com/vt?lyrs=h@159000000,traffic|seconds_into_week:-1&style=3&x={x}&y={y}&z={z})
- Google Roads: (https://mt1.google.com/vt/lyrs=h&x={x}&y={y}&z={z})
- Bing maps: (http://ecn.dynamic.t0.tiles.virtualearth.net/comp/CompositionHandler/{q}?mkt=en-us&it=G,VE,BX,L,LA&shading=hill)
- Bing Satélite: (http://ecn.t3.tiles.virtualearth.net/tiles/a{q}.jpeg?g=0&dir=dir_n’)
- Carto Positron: (https://cartodb-basemaps-a.global.ssl.fastly.net/light_all/{z}/{x}/{y}.png)
- CARTO dark: (http://a.basemaps.cartocdn.com/dark_all/{z}/{x}/{y}.png)
- ESRI Imagery/Satellite: (https://server.arcgisonline.com/ArcGIS/rest/services/World_Imagery/MapServer/tile/{z}/{y}/{x})
- ESRI National Geographic: (http://services.arcgisonline.com/ArcGIS/rest/services/NatGeo_World_Map/MapServer/tile/{z}/{y}/{x})
- ESRI Physical: (https://server.arcgisonline.com/ArcGIS/rest/services/World_Physical_Map/MapServer/tile/{z}/{y}/{x})
- ESRI Streets: (https://server.arcgisonline.com/ArcGIS/rest/services/World_Street_Map/MapServer/tile/{z}/{y}/{x})
- ESRI Terrain: (https://server.arcgisonline.com/ArcGIS/rest/services/World_Terrain_Base/MapServer/tile/{z}/{y}/{x})
- ESRI Topo: (https://server.arcgisonline.com/ArcGIS/rest/services/World_Topo_Map/MapServer/tile/{z}/{y}/{x})
- ESRI Transportation: (https://server.arcgisonline.com/ArcGIS/rest/services/Reference/World_Transportation/MapServer/tile/{z}/{y}/{x})
- Stamen Terrain: (http://a.tile.stamen.com/terrain/{z}/{x}/{y}.png)
- Stamen Toner: (http://tile.stamen.com/toner/{z}/{x}/{y}.png)
- Stamen Watercolor: (http://tile.stamen.com/watercolor/{z}/{x}/{y}.jpg)

###	Uso de herramientas básicas tanto vectorial como ráster
###	Búsqueda y aplicación de complementos para la descarga, análisis y visualización de datos espaciales.

- QuickMapServices: Mapas bases
- mmqgis: Herramientas vectoriales
- Digitizing tools: Herramientas para la digitalización
- Semi-automatic classification plugin: Clasificación para imágenes de satélite
- autoSaver: Guardado automático del proyecto
- Data Plotly: Generación de gráficos
- QuickOSM: Descarga datos OSM
- Spanish Inspire Catastral Downloader: Descarga datos catastro
- LAStools: Herramientas para LIDAR
- Etc..

###	Proceso de composición de mapas y otros formatos de salida

## Materiales
{:toc}
Capas de información en diferentes formatos que se utilizarán durante el curso.



Estas capas han sido descargadas desde webs de datos abiertos
- [Datos abiertos Ayuntamiento de Madrid](https://datos.madrid.es/portal/site/egob/)
- [Datos abiertos Comunidad de Madrid](https://www.comunidad.madrid/gobierno/datos-abiertos)
- [Datos abiertos Gobierno de España](https://datos.gob.es/)
- [Datos abiertos Esri España](https://opendata.esri.es/)
- [The World Bank Data Catalog](https://datacatalog.worldbank.org/)


## Recursos
{:toc}
### Webs
{:toc}
- [Estilos oficiales para QGIS](https://plugins.qgis.org/styles/)
- [Plugins](https://plugins.qgis.org/plugins/)
- [Web de Topi Tjukanov](https://tjukanov.org/) Promotor del #30daymapchallenge
- [Web de Anita Graser - Movement Data](https://anitagraser.com/)
- [QGIS Hub - Styles & layouts](http://qgis-hub.fast-page.org/index.php?i=1)
- [Canal YouTube de Klas Karlsson](https://www.youtube.com/user/klakar70)

### Libros
{:toc}
- [QGIS Map Desing (Anita Graser & Gretchen N. Peterson)](https://locatepress.com/qmd2)
