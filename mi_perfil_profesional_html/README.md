# Portafolio Profesional - Mathews Pastor
# Objetivo:
El objetivo de este proyecto es la creación de un portafolio web personal y profesional para presentar mi perfil, formación académica, áreas de interés y contáctos. Además, de usar este proyecto como un ejercicio práctico de las habilidades aprendidas hasta el momento en la materia de Programación Web.

# Tecnologías Utilizadas
* HTML5
* CSS
* Docker/Docker Desktop
* Nginx 
* Git/Github

# Estructura del Proyecto
```text
/
|- mi_perfil_profesional_html
|-- index.html
|-- Dockerfile
|-- README.md
|-- Recursos/
    |-- perfil.jpg
    |-- fondo.jpg
|-- css/
    |-- perfil.css
```
# Instrucciones para construir y ejecutar la imagen Docker
1. Construir la imagen localmente: docker build -t mathewspastor-perfil-profesional .
2. Construir el contenedor: docker run -d -p 8080:80 mathewspastor-perfil-profesional
3. Finalmente acceder al sitio ingresando en la web con: http://localhost:8080

# Enlace a Docker Hub.
Enlace de la imagen pre-construida desde mi computador: https://hub.docker.com/repository/docker/mthwssd/mi-perfil-profesional
