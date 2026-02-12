[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/ZxhVwR7F)


## DOCUMENTACION -- ALEX EXAMEN FINAL

## Despliegue en local

Siguiendo la guia dada, he creado los archivos necesarios y que vamos a usar
Como el objetivo es desplegar en local

- Api-Actors
He modificado  las properties por defecto comentandolos y añadiendo la variable nueva
- spring.profiles.active=local

- LOCAL
He añadido las variables de postgre como indica en el ejercicio

- En el Compose-local: 
He levantado el contenedor para usar la base de datos postgres. 
En las properties LOCAL tengo los datos que va a usar ese contenedor.
En las properties.local he añadido los datos de postgres
Tambien he añadido el puerto para cada uno, ya que al levantar los dos servicios a la vez chocan


## En api - movies

He seguido el mismo camino que el anterior,
Pero he cambiado los nuevos datos de la base de datos
He cambiado el puerto
He hecho lo mismo en las properties.local, pero con datos de movies
Tambien he añadiedo el puerto diferente para evitar que choquen


## Compose-local

- Solo he creado tres servicios
Los dos servicios de la base de datos y la del frontend

En el frontend he llamado las dos URL que habia en el backend de cada uno
y asi poder llamarlo en el frontend mostrando sus datos


## Despliegue en modo Dev

## Api-autors
- Siguiendo en con el ejercicio he rellenado los datos del properties del pre
- El objetivo era que con los datos de una base de datos en postgres
- Luego ser llamado en el contendero de la api
- Tambien el servicio de la base de datos se crea en el compose-pre

Con esto levantamos los contenedores y el modo dev, deberia mantener la api-actors,
la base de datos crea en postgre, y el frontend

- El objetivo es hacer lo mismo que el anterior ejercicio pero que la api este en un contenedor
- La base de datos ya lo hemos hecho antes es lo mismo
- El frontend tambien, solo que ahora apunta a la ruta data por la api

## Api- movies

- Hacemos lo mismo que antes, pero cambiando los datos
- Nueva base de datos










