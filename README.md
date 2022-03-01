# OSM ES Map : Motivo
OSM ES Map nace de la adaptación del mapa de la comunidad catalana a mostrar cualquier tipo de información temática, aprovechando la base de datos de Openstreetmap.

# 0-La Base de datos: Openstreetmap
OSM (Openstreetmap) no es un mapa, es una base de datos de puntos y líneas geolocalizados, que entre otras cosas se puede aprovechar para realizar mapas (renderizaciones). Pero también se pueden aprovechar los datos. Todo ello se hace con claves, valores y relaciones en estos puntos y líneas.

# 1-Mapa

-Mapa basado en [Bicycle tags map](https://wiki.openstreetmap.org/wiki/Bicycle_tags_map)

-Con modificaciones de [Ramiro Balado](https://github.com/Qjammer)

-Versión nueva Openlayers hecha por [Ripollx](https://github.com/Ripollx)

-Posibilidad de añadir JSONs hecha por [Hugoren Martinako ](https://github.com/Crashillo)

-Consultas complejas añadidas por [Ismael Luceno](https://github.com/ismaell)

-Ideas adicionales por [yopaseopor](https://github.com/yopaseopor)

El mapa nos permite la muestra de elementos determinados personalizables teniendo como fondo varios mapas distintos.

Directamente se puede modificar la página editando los archivos correspondientes:

* index.html contiene el esqueleto de la página.
* index.js contiene el orquestador para utilizar OpenLayers (sólo se requiere modificar para añadir nuevas funcionalidades).
* config.js contiene la definición de las capas, idioma y características que se quieren mostrar.

# [Ejemplo del mapa funcionando](https://osm-es.github.io/osmesmap)

# Agradecimientos

A la [Comunidad Catalana de Openstreetmap](https://t.me/osmcat) y a [OSM España](https://t.me/osmes) por permitir estos mapas, así como a los desarrolladores que han colaborado. 