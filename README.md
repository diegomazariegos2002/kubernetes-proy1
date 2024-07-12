# MANUAL TÉCNICO

## INSTALACIÓN DE HERRAMIENTAS

*  Visual Studio Code
    * Spring Boot Extension Pack
    * Java Extension Pack

*  Java JDK 22

*  Maven (opcional)

*  Git

*  Postman

* Docker Desktop

## LEVANTANDO DE PROYECTO

### Pull y ejecución de bases de datos

`docker network create spring`

`docker run -d -p 3307:3306 --name mysql --network spring -e MYSQL_ROOT_PASSWORD=sasa -e MYSQL_DATABASE=msvc_usuarios mysql`

`docker run -p 5532:5432 --name postgres --network spring -e POSTGRES_PASSWORD=sasa -e POSTGRES_DB=msvc_cursos -d postgres`

