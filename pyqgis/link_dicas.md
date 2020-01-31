# Adicionando Dados Vetoriais

```python
path = '/Users/marcello/code/qgis/pbdata/pb.gpkg|layername=municipios'

municipios = iface.addVectorLayer(path, 'municipios', 'ogr')

municipios.featureCount()

filtro = "nome ='Campina Grande'"

municipios.setSubsetString(filtro)

municipios.setSubsetString('')
```

https://docs.qgis.org/testing/en/docs/pyqgis_developer_cookbook/loadlayer.html#id1

https://github.com/All4Gis/QGIS-cheat-sheet/blob/master/QGIS3.md

https://github.com/volaya/qgis-python-course

https://github.com/meraioth/proyecto_semestral_gis

https://gitlab.com/geocastbrasil/livepyqgis/tree/master

https://courses.spatialthoughts.com/pyqgis-in-a-day.html