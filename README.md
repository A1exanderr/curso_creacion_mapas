# ENTORNO DE PRODUCCION

> Creacion de red por primera ves
```
docker network create app_network_produccion
```
>Verficacion de contenedores en la red
```
docker network inspect app_network_produccion
```
>Para cargar todas la carpetas con los proyectos requeridos
```
git submodule update --init --recursive 
```