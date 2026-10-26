docker build -t greeter:v1 -f lessons/02-docker-basics/homework/greeter/Dockerfile lessons/02-docker-basics/homework/greeter


docker run -d --name greeter -p 9000:8000 greeter:v1

docker run -d --name greeter -p 9000:8000 -e GREETING=Shalom greeter:v1

Shalom, Rivka!






