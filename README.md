![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)

# Individual Project - Henry Videogames

<p align="right">
  <img height="200" src="./videogame.png" />
</p>

## Objetivos del Proyecto

- Construir una App utlizando React, Redux, Node y Sequelize.
- Aprender mejores prácticas.
- Practicar el workflow de GIT.

## Comenzando

 - Clonar el repositorio en sus computadoras para comenzar

__IMPORTANTE:__ Es necesario contar minimamente con la última versión estable de Node y NPM.

Actualmente las versiónes necesarias son:

- __react-router-dom__: 5.2.0

## BoilerPlate

El boilerplate cuenta con dos carpetas: `api` y `client`. En estas carpetas estará el código del back-end y el front-end respectivamente.

En `api` crear un archivo llamado: `.env` que tenga la siguiente forma:

```env
DB_USER=usuariodepostgres
DB_PASSWORD=passwordDePostgres
DB_HOST=localhost
```

Reemplazar `usuariodepostgres` y `passwordDePostgres` con tus propias credenciales para conectarte a postgres. 
Adicionalmente será necesario que creen desde psql una base de datos llamada `videogames`

## Enunciado
 la api externa [rawg](https://rawg.io/apidocs) 
 
- Buscar videjuegos
- Filtrarlos / Ordenarlos
- Agregar nuevos videojuegos

__IMPORTANTE__: Para poder utilizar esta API externa es necesario crearse una cuenta para obtener una API Key
