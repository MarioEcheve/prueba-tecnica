Instalacion

1 - existe un archivo llamado docker-compose, posee toda la arquitectura , bd , backend y frontend.
2 - para poder ejecutar este archivo se debe tener instalado docker en el equipo local
3 - teniendo instalado  docker nos situamos donde se encuentra el archivo docker-compose y ejecutamos el siguiente comando
    docker-compose up -d 
        al ejecutar esto se desplegaran servivioc:
            pgAdmin en la direccion : http://localhost:81
            backend en la direccion : http://localhost:8080
            frontend en la direccion : http://localhost:80
    si desea detener el docker-comando ejecute:
        docker-compose down
    a considerar:
        la informacion esta siendo efimera, no implemente un volumen.

Respositorios

links de github de los proyectos
    front: https://github.com/MarioEcheve/encuesta-front.git
    backend: https://github.com/MarioEcheve/encuesta-backend.git

repositorio frontend : 
repositorio backend : 
