# LAMP Docker Compose

Este repositorio contiene la configuracion para los contenedores de Apache, Mysql y PHP con Phpmyadmin.

## Configuracion

El repositorio tiene un archivo .env el cual necesita ser configurado para indicar las accesos a phpmyadmin y mysql.

## Instalacion

Se clona este repositorio y posteriormente se ejecuta:

```
./start-docker.sh
```

Esto prepara los contenedores y los lanza para la ejecucion. Para finalizar los contenedores se ejecuta:

```
./stop-docker.sh
```
