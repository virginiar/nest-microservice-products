<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Nest-MicroServices - Products microservice

Repositorio para el microservicio Products de la aplicación Products realizada en [Nest](https://github.com/nestjs/nest). 
Basado en el curso de "NestJs + Microservicios: Aplicaciones escalables y modulares" de [DevTalles](https://cursos.devtalles.com/) en Udemy.

## Configuración del proyecto

1. Instalar NestJS CLI

```bash
$ npm i -g @nestjs/cli
```
2. Clonar el repositorio

3. Instalar las dependencias

```bash
$ npm install
```

4. Crear un archivo ```.env``` basado en ```.env.template```.

5. Ejecutar la migracion de Prisma

```bash
$ npx prisma migrate dev
```

6. Ejecutar el proyecto

```bash
$ npm run start:dev
```

## Aspectos estudiados

En este repositorio se trabajan los siguientes aspectos de Nest:
-	CRUD
-	MessagePattern
-	SQLite
-	Prisma con Nest
-	Migraciones
-	Transformar REST a Microservicio
-	Aplicaciones Híbridas Rest + Microservicios
-	GitHub - Organizaciones

## Librerías utilizadas

Para las validaciones se utilizan:

```bash
$ npm install class-validator class-transformer
```

Para la gestión de variables de entorno:

```bash
$ npm install dotenv
```

Para los esquemas de validación:

```bash
$ npm install joi
```

La gestión de la base de datos se realiza con Prisma:
```bash
$ npm install prisma --save-dev
$ npx prisma init
$ npx prisma migrate dev --name init

$ npm install @prisma/client
$ npx prisma generate
$ npm install @prisma/adapter-better-sqlite3
```