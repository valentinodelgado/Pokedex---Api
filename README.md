<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar el repositorio
2. Ejecutar 
```
npm install
```
3. Tener Nest CLI instalado
```
nest i -g @nestjs/cli
```

4. Levantar la base de datos
```
docker-compose up -d
```

5. Clonar el archivo __.env.template__ y renobrar la copia a __.env__

6. LLenar las variables de entorno deinidas en el __.env__

7. Ejecutar la aplicacion en dev:
```
npm run start:dev
```
8. Reconstruir la base de datos con la semilla
```
http://localhost:3000/api/seed
```

## Stack usado
* MongoDB
* Nest Js