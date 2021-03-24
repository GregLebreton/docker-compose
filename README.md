                                       ### DOCKER-COMPOSE WORDPRESS ###


# Installation Docker-compose:
        
        $ sudo curl -L https://github.com/docker/compose/releases/download/1.25.3/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
        
        $ sudo chmod +x /usr/local/bin/docker-compose
        
        $ docker-compose --version


# Sujet: 

        - utiliser docker-compose pour manier plusieurs containers interagissant entre eux
            * Un container Nginx en front servant 
            * un container Wordpress s'appuyant sur 
            * un container MariaDB
 
 
# Outils: 

        * Docker
        * Docker-compose

# Processus:

        $ docker-compose up
        
  
# visiter:

        http://localhost:8080
