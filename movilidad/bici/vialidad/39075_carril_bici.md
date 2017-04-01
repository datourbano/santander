### [datourbano](https://github.com/datourbano): Carril bici - Santander

* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/ubicacion_18.png) Ciudad: [Santander](https://datourbano.github.io/santander)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/origen_18.png) Origen: [Portal de datos abiertos del Ayuntamiento de Santander](http://datos.santander.es/dataset/?id=carril-bici)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/calendario_18.png) Fecha: 30-03-2017
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/carpeta_18.png) Repositorio: https://github.com/datourbano/santander/tree/master/movilidad/bici/vialidad
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/enlace_18.png) LinkedData: [39075_carril_bici.geojson](https://raw.githubusercontent.com/datourbano/santander/master/movilidad/bici/vialidad/39075_carril_bici.geojson)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/mapa_18.png) Visualización: [Carril bici - Santander](https://datourbano.github.io/santander/movilidad/bici/vialidad/39075_carril_bici)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/notas_18.png) Notas:

 (Portal de datos abiertos del Ayuntamiento de Santander)

  > "Tramos de Carril Bici desplegados en el Municipio de Santander.".
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/herramienta_18.png) Tratamiento:

  Los datos fuente se han descargado en formato CSV. En él, las geometrías se incluyen dentro de un atributo, expresadas en formato WKT [(*Well-known text*)](https://es.wikipedia.org/wiki/Well_Known_Text). Se observa que este campo incluye caracteres extra del tipo (*"\"*) que ha sido necesario eliminar para poderlo procesar geográficamente.

   Las coordenadas originales están definidas en el sistema geográfico de referencia *UTM European 1950 Huso 30Norte*, transformándose al sistema ETRS89 (SGR oficial de España) aplicando una transformación precisa *NTV2* con la rejilla del IGN Península y Baleares.

  La información resultante se han convertido a formato GeoJSON, manteniéndose todo el conjunto de atributos asociados.

  Los datos finales se ofrecen en coordenadas geográficas OGC CRS:84 (EPSG:4326 lon-lat), con una codificación de caracteres: UTF8

  La descripción geométrica de los carriles bici representa los bordes de los mismos, ofreciendo una muy buena exactitud y precisión geográfica, si bien se comprueba que existen algunos pequeños tramos desactualizados, no correspondiendo en estos casos su trazado digital con la realidad terreno.