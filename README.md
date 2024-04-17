

## Moodle con Docker Compose
Este repositorio te permite ejecutar una instancia local del LMS Moodle utilizando Docker Compose, Este entorno incluye:

- MariaDB como base de datos
- Moodle version 4.3.3
- phpMyAdmin para gestionar la base de datos

## Instrucciones

**Clonar el repositorio:**
```bash
git clone https://github.com/froddo-dev/docker-moodle-dev.git
```

**Iniciar los contenedores:**
```bash
docker-compose up -d
```

### Acceder a Moodle:
- Url: `http://localhost:8080` 
- Usuario: `admin` 
- Contraseña: `passw0rd!` 

### Acceder a phpMyAdmin
- Url: `http://localhost:8081` 
- Usuario: `root` 
- Contraseña: `moodle` 

### Comandos útiles

**Iniciar los contenedores:**
```bash
docker-compose up -d
```

**Detener los contenedores:**
```bash
docker-compose down
```

**Ver el estado de los contenedores:**
```bash
docker-compose ps
```

**Ver los logs de todos los contenedores:**
```bash
docker-compose logs -f
```

## Documentación
- Docker: [Documentación Docker Compose](https://docs.docker.com/compose/)
- Moodle: [Documentación Moodle](https://docs.moodle.org/)
- MariaDB: [Documentación MariaDB](https://mariadb.com/kb/en/documentation/)

## Notas:
- Las contraseñas, usuarios, puertos y otras opciones se pueden configurar modificando el archivo docker-compose.yml. 
- Con este repositorio y los comandos mencionados, puedes crear y administrar de manera eficiente tu entorno de desarrollo local del LMS Moodle utilizando Docker Compose.
