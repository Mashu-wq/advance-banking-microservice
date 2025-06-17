1. <packaging>ja<packaging>
2. mvn clean install
3. docker build . -t username/cards:v4
4. docker run -d -p 8888:7777 username/cards:v4
5. docker ps
6. docker-compose up -d
7. docker compose down