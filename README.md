# 3D i desktop GIS

Vi skal lage en 3D visualisering av terrengmodell i desktop GIS. Det finnes en rekke avanserte GIS platforme til desktop. Tidligere har ESRI dominert markedet med [ArcGIS](http://www.esri.com/software/arcgis) - [MapInfo](http://www.mapinfo.com/) er også stor. Etterhvert har Open Source alternativene vokst seg store - blant de mest populære er [Quantum GIS / QGIS](http://www.qgis.org/en) og [GRASS GIS](http://grass.osgeo.org/).

## QGIS og data
Gå til http://www.qgis.org/en/site/forusers/download.html, last ned og installer QGIS. Det finnes til både Linux, Mac og Windows.

Last ned terrengmodell i fra Kartverket her:
http://data.kartverket.no/download/content/digital-terrengmodell-10-m-utm-33

For å laste ned fra Kartverket, må du først [opprette ny bruker](http://data.kartverket.no/download/user/register) og logge inn. Velg de områder du ønsker terrengmodell for og klikk på "Legg i kurv > Se kurven > Bestill > laste ned filene her > Download" og du kan nå lagre data som DEM fil (xyz text koordinater), ligger her som [qgis/data/6900_2_10m_z33.dem](qgis/data/6900_2_10m_z33.dem).

![kv](img/kv01.png)