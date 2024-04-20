<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar el repositorio
2. Ejecutar

```
yarn install
```
3. tener Nest CLI instalado

``` 
npm i -g @nestsjs/cli
```
4. levantar la base datos

```
docker-compose up -d

```
5. Clonar el archivo __.env.template__ y renombrar la copia a __.env__ 

6. Llenar las variables de entorno definindas en el __.env__ 

7. Ejecutar la aplicación en dev: 

```
yarn start:dev

```

8. Reconstrui la base de datos con la semilla

```
http://localhost:3000/api/v2/seed

```

# Stack usado 
* MongDB
* Nest