Ola mundo.
Alunos   Anderson, Jose, Lucas, Gabriel Roggia
Foi inserido os seguintes comandos no linux pelo gerente
-1-  docker swarm ini --advertise-addr 100.64.29.71
-3-  sudo docker ls
-4-  touch docker-compose.yml
-5-  nano docker-compose.yml   + o codigo
-6-  sudo docker stack deploy -c docker compose.yml myapp
-7-  sudo service scale myapp_web=5
-8-  sudo docker node ls  
-10-  sudo docker service ls
-11-  sudo docker service ps myapp_web 
-12-  docker logs 606f742457f7
-



Foi inserido os seguintes comandos no linux pelos trabalhadores
- 2- sudo docker swarm join --token SWMTKN-1-19hiarkhoi5bwjnlop0w3uz8mnuu21adxfbaz9fztw6quti2xw-e3i0e8ugevslosfd28ko20neq 100.69.29.71.
- 9- sudo docker swarm leave
