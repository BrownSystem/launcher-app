## Prod

1 - Clonar el repositorio
2 - Crear un.env basado en el .env.template
3 - Ejecuta el comando

```
    docker compose -f docker-compose.prod.yml build
```

4 - Inicia el contenedor

# Esto sirve para que las imagenes puedan levantarse mucho mas rapido.

```
    docker compose -f docker-compose.prod.yml up
```

5 - Ejecuta el comando para TEST

```
    docker compose -f docker-compose.yml exec build || up
```

6 - Tener en cuenta que si se quiere usar el comando de arriba, se debe actualizar los puertos para la conexion de DB en cada MS.

7. PROBANDO CAMBIOS

[HACER BUILD DE DOCKER NUEVO Y SUBIR A DOVKER HUB]

frontend []
client-gateway []
auth-ms []
