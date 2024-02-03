```console

docker swarm init --advertise-addr 192.168.0.XX

cd web

docker build -t phptesteapp .

docker stack deploy -c compose.yaml servico-web

```
