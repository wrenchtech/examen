
## Requisitos previos
Debes tener instalado Docker Desktop en tu sistema.

## Instrucciones de uso
1. Clona este repositorio en tu máquina local:

```git clone https://github.com/angelHerreraP/Proyecto-Parcial```

2. Navega al directorio del proyecto:

```cd proyecto-docker-node-postgres-pgadmin```

3. Ejecuta el siguiente comando para iniciar los servicios:

```docker-compose up```

Accede a la aplicación Node.js desde tu navegador web:

```URL: http://localhost:3000```

Accede a PGAdmin para administrar la base de datos PostgreSQL:

```URL: http://localhost:8080```

Credenciales por defecto:
Correo electrónico: admin@admin.com
Contraseña: admin

## Estructura del proyecto

docker-compose.yml: Archivo de configuración de Docker Compose que define los servicios de la aplicación.

index.js: Archivo principal de la aplicación Node.js.

package.json: Archivo de configuración de Node.js con las dependencias y los scripts de inicio.


