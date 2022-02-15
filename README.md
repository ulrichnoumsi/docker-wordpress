# docker-wordpress
Deploiement de wordpress et d'une base de donnee

1. installation de docker
---
sudo bash docker_install.sh
---
2. installation de docker-compose
---
sudo curl -L "https://github.com/docker/compose/releases/download/1.23.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/bin/docker-compose && sudo chmod +x /usr/bin/docker-compose
---
3. lancer le fichier docker-compose.yml
---
sudo docker-compose up
---
