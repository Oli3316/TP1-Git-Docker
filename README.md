
# Trabajo Práctico N° 1 - Git y Docker

## Descripción

Aplicación web estática desarrollada para la materia
Ingeniería de Software.

El proyecto consiste en una página web que permite
cambiar el color de fondo mediante un botón.

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- Git y GitHub
- Docker
- Nginx

## Requisitos

- Git instalado
- Docker Desktop instalado y funcionando
- Navegador web

## Construcción de la imagen Docker

Desde la carpeta del proyecto, ejecutar:

```bash
docker build -t tp1-git-docker .
```

## Ejecución del contenedor

```bash
docker run -d --name tp1-web -p 8080:80 tp1-git-docker
```

## Acceso a la aplicación

Abrir en el navegador:

http://localhost:8080

## Verificar el contenedor

```bash
docker ps
```

## Detener el contenedor

```bash
docker stop tp1-web
```

## Control de versiones

Se utilizó Git para registrar los avances
del desarrollo mediante commits.

El código fuente se publica en GitHub.
