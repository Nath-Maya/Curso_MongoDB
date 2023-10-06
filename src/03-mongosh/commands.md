
## Connect to container

```sh=
docker-compose exec mongodb bash
```
el comando exe es para ejecutar  , seguido del servicio, en este caso mongodb. Luego ejecutamos la terminal tipo bash

## Connect with mongosh

```sh
mongosh "url de mi base de datos" 
```


```sh
show dbs // muestra las bases de datos
show collections // muestra las colleciones dentro de una base de datos. 
```

## Use database

```sh
use("nombre de base de datos")
```