# 42docs

## netwhat :
  
  - cours sur le projet : https://github.com/rchallie/netwhat/blob/master/research.md
  - calculateur : https://cric.grenoble.cnrs.fr/Administrateurs/Outils/CalculMasque/
  - cours openclassrooms : https://openclassrooms.com/fr/courses/857447-apprenez-le-fonctionnement-des-reseaux-tcp-ip
  
 ## ft_server : 

   ### Lancement docker :
    docker build -t name .
    docker run -it -p port:port name
    docker cp <containerID>:/chemin_file_container /chemin_file_host
  - Les bases de dockers -- 1 : https://www.youtube.com/watch?v=SXB6KJ4u5vg&t=256s
  - Les bases de dockers -- 2 : https://www.youtube.com/watch?v=cWkmqZPWwiw&t=284s
  - docker : https://www.youtube.com/watch?v=XgKOC6X8W28&t=1131s
  - nginx : https://www.youtube.com/watch?v=YD_exb9aPZU&t=870s
  - ssl -- Découverte du protocole ssl  : https://www.youtube.com/watch?v=_UpuZ0Y3k-c&t=418s
  - ssl -- tool qui configue automatiquement un protocole ssl  : https://github.com/FiloSottile/mkcert
  - ssl -- command openssl (apt-get install openssl) : https://help.tableau.com/current/server/en-us/ssl_cert_create.htm
  - nginx, mysql, php : https://www.digitalocean.com/community/tutorials/how-to-install-linux-nginx-mysql-php-lemp-stack-ubuntu-18-04
  - phpmyadmin : https://www.digitalocean.com/community/tutorials/how-to-install-phpmyadmin-from-source-debian-10
  - mysql command : http://g2pc1.bu.edu/~qzpeng/manual/MySQL%20Commands.htm
  
## cub3d : 

  - mlx : https://harm-smits.github.io/42docs/libs/minilibx/introduction.html
  - Tuto raycasting : https://lodev.org/cgtutor/raycasting.html
  - algorithm DDA : https://en.wikipedia.org/wiki/Digital_differential_analyzer_(graphics_algorithm)
  - raycasting theorie : https://guy-grave.developpez.com/tutoriels/jeux/doom-wolfenstein-raycasting
  - raycasting sites interessant : https://permadi.com/1996/05/ray-casting-tutorial-9/ https://www.permadi.com/tutorial/raycast/rayc9.html
  - raycasting youtube : https://www.youtube.com/watch?v=gYRrGTC7GtA&t=50s
  - generateur de map cub3d : https://github.com/revarsavr/mapgen
  - algo pour faire un ligne d'un point A a un point B : https://en.wikipedia.org/wiki/Bresenham%27s_line_algorithm
  - minilibx linux : https://github.com/42Paris/minilibx-linux.git

 ## libasm : 
 
 - instruction : https://en.wikipedia.org/wiki/X86_instruction_listings
 - tuto : https://cs.lmu.edu/~ray/notes/nasmtutorial/
 - register : https://en.wikibooks.org/wiki/X86_Assembly/X86_Architecture
 - syscall for linux : https://blog.rchapman.org/posts/Linux_System_Call_Table_for_x86_64/
 - informations intéressantes : https://www.lacl.fr/tan/asm
 - jump if ?? : https://www.gladir.com/LEXIQUE/ASM/jumpif.htm
 - Testeur : https://github.com/cacharle/libasm_test
 - cours : https://cs.brown.edu/courses/cs033/docs/guides/x64_cheatsheet.pdf
        
        First Argument: RDI
        Second Argument: RSI
        Third Argument: RDX
        Fourth Argument: RCX
        Fifth Argument: R8
        Sixth Argument: R9
        le reste est empile sur la stack

## ft_services :
  
 - https://stackoverflow.com/questions/41509439/whats-the-difference-between-clusterip-nodeport-and-loadbalancer-service-types
 - https://metallb.universe.tf/configuration/
 - https://medium.com/faun/metallb-configuration-in-minikube-to-enable-kubernetes-service-of-type-loadbalancer-9559739787df
 - https://kubernetes.io/fr/docs/tutorials/hello-minikube/
 - https://stackoverflow.com/questions/52310599/what-does-minikube-docker-env-mean
 - https://stackoverflow.com/questions/56392041/getting-errimageneverpull-in-pods
 - https://stackoverflow.com/questions/42564058/how-to-use-local-docker-images-with-minikube
 - https://medium.com/faun/metallb-configuration-in-minikube-to-enable-kubernetes-service-of-type-loadbalancer-9559739787df
 - https://linoxide.com/containers/deploy-mysql-on-kubernetes/
 - https://stackoverflow.com/questions/29420870/install-mysql-in-dockerfile
 - https://aws.amazon.com/fr/blogs/france/demystifier-entrypoint-et-cmd-dans-docker/
 - https://www.howtogeek.com/117435/htg-explains-the-linux-directory-structure-explained/
 - https://emcitv.com/bible/strong-biblique-grec-kubernetes-2942.html
 - http://dba.fyicenter.com/faq/mysql/What-Is-MySQL-Server-Daemon-mysqld.html
 - https://metallb.universe.tf/usage/
 - https://www.serverlab.ca/tutorials/containers/kubernetes/deploy-phpmyadmin-to-kubernetes-to-manage-mysql-pods/
 - https://www.a2hosting.com/kb/developer-corner/mysql/managing-mysql-databases-and-users-from-the-command-line
 - https://kubernetes.io/docs/tasks/run-application/run-single-instance-stateful-application/
 - https://blog.ruanbekker.com/blog/2017/08/26/building-a-alpine-nginx-php-fpm-image-on-docker-for-php-applications/
 - https://github.com/cloudogu/k8s-diagrams
 - https://www.ionos.fr/digitalguide/serveur/know-how/quest-ce-quun-reverse-proxy-le-serveur-reverse-proxy/
 - https://phil.writesthisblog.com/https-certificat-ssl-selfsigned/
 - https://kubernetes.io/docs/tasks/inject-data-application/distribute-credentials-secure/
 - https://devopssec.fr/article/cours-complet-apprendre-technologie-docker#begin-article-section
 - https://devopssec.fr/article/cours-complet-apprendre-orchestrateur-kubernetes-k8s

## push_swap :

- fichier de correction : https://github.com/42sommecaise/42Docs/blob/master/message.txt
- https://fr.wikipedia.org/wiki/Algorithme_de_trihttps://fr.wikipedia.org/wiki/Algorithme_de_tri

## philosophers :

- Sur les threads, très bon guide de démarrage https://franckh.developpez.com/tutoriels/posix/pthreads/
- Sur les sémaphores https://sites.uclouvain.be/SyllabusC/notes/Theorie/Threads/coordination.html
