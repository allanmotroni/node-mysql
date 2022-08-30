# node-mysql

# Rodar na máquina

docker run -it -v ./node:/usr/src/app node:15 bash

# Rodar o app node de dentro do container

node index.js

# Subir a stack
docker-compose up -d --build
