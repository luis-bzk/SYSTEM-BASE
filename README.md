
<h1 align="center"><b>SynergyControl</b> - La unión inteligente para gestionar, controlar y potenciar tu negocio</h1>

<p align="center">Servicio API del lado del backend</p>

- [Introducción](#introducción)
- [Instalación](#instalación)
- [Configuración](#configuración)
- [Crear Base de Datos.](#crear-base-de-datos)
- [MongoDB URL](#mongodb-url)

## Introducción

Base para la creacion de sistemas con TypeScript y NodeJs con aquitectura hexagonal

## Instalación

Para poder realizar la reconstrucción e instalación de los módulos se requiere ejecutar los siguientes comandos

```bash copy
yarn install
yarn dev
```

## Configuración

Cambiar el nombre del archivo __.env.template__ a __.env__ y establecer las variables de entorno

## Crear Base de Datos.

Es necesario crear una base de datos, en este caso se hará uso de Docker para crearla en local.

```text
docker compose up -d
```

* '-d' hace referencia a la propiedad __"detached"__ 

## MongoDB URL

Para la conexión con la herramienta MongoDB compass se utilizara la URI de mongo, si es cloud se utilizara la URI proporcionada por mongo.

En local se hace uso de la siguiente URI:

```bash
mongodb://localhost:27017/SRCVP
```
