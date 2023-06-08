
Docker Build Command: 
    $> docker build -t docker-practice:latest

Docker Run Command:
    $> docker run --rm --name dockerpractice 8080:8080 docker-practice:latest

Docker Stack Deploy Command:
    $> docker stack deploy -c docker-compose.yaml dockerpractice 

Application URL:
    localhost:8080