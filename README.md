

## Moodle con Docker Compose
Este repositorio te permite ejecutar una instancia local de Moodle utilizando Docker Compose, facilitando el desarrollo y las pruebas de tu entorno Moodle.

## Instrucciones

**Clonar el repositorio:**
```bash
git clone https://github.com/froddo-dev/docker-moodle-dev.git
```

**Iniciar los contenedores:**
```bash
docker-compose up -d
```

**Acceder a Moodle:** \
Url: `http://localhost:8080` \
Usuario: `admin` \
Contraseña: `passw0rd!` 

**Acceder a phpMyAdmin** \
Url: `http://localhost:8081` \
Usuario: `root` \
Contraseña: `moodle` 

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

### Documentación:
Docker: `https://docs.docker.com/compose/` \
Moodle: `https://docs.moodle.org/` 

**Notas:** 
- Las contraseñas y usuarios se pueden configurar puertos y otras opciones modificando el archivo docker-compose.yml. 

**Con este repositorio y los comandos mencionados, puedes crear y administrar de manera eficiente tu entorno de desarrollo local de Moodle utilizando Docker Compose.**
