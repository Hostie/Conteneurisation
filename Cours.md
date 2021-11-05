Virtualisation

	- Technologie
	- Representation virtuelle d’un serveur

Embarque tous les composants d’un serveur de manière virtuelle/


Conteneurisation

-Methode de stockage
-Methode de transport

Espace d’éxécution, n’embarque que ce qui est demandé.

Docker

build = créer une archive
tag = nom image
docker run = lancer

-------  docker run -(d) -p 8000:80 -v pwd/conf:nginxconf -v pwd/html:html       -------------

https://vsupalov.com/docker-arg-env-variable-guide/

Projet chaos = docker system prune -a

docker run -v "$(pwd)/data:/opt" base

ARG va être utilisé dans le build
ENV est dans RUN

docker exec-it = rentre dans le transport


Scalabilité : gestion de la montée en charge


Registry (DOckerHub) : passage d'environnement de DEV en local à un environnement de prod avec une image buildée 
CI/CD : Continuous integration - Continuous Deploy


