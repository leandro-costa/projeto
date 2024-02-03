```console

docker swarm init --advertise-addr 192.168.0.XX

docker service create --name registry --publish published=5000,target=5000 registry:2

docker compose up -d

docker compose ps

docker compose down

docker compose push

docker stack deploy --compose-file compose.yaml testeapp

```
