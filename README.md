Ola mundo.
Foi inserido os seguintes comandos no linux pelo gerente
- docker swarm ini --advertise-addr 100.69.29.71
- sudo docker ls
- touch docker-compose.yml
- nano docker-compose.yml   + o codigo
- sudo docker stack deploy -c docker compose.yml myapp
- sudo service scale myapp_web=5
- sudo docker node ls  
- sudo docker service ls
- sudo docker service ps myapp_web 
- docker logs 606f742457f7
-



Foi inserido os seguintes comandos no linux pelos trabalhadores
sudo docker swarm join --token SWMTKN-1-19hiarkhoi5bwjnlop0w3uz8mnuu21adxfbaz9fztw6quti2xw-e3i0e8ugevslosfd28ko20neq 100.69.29.71.
sudo docker swarm leave
