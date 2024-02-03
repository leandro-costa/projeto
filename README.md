```console

docker swarm init --advertise-addr 192.168.0.XX

docker service create --name registry --publish published=5000,target=5000 registry:2

docker compose up -d

docker compose ps

docker compose down

docker compose push

docker stack deploy --compose-file compose.yaml testeapp

docker service ls

docker service ps testeapp_web

docker service scale testeapp_web=1
docker service scale testeapp_web=5

docker service rm testeapp_web
```
