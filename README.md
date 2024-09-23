# Estudos MongoDB
Para iniciar o serviço do Mongo, basta rodar o comando abaixo:

```powershell
docker-compose up -d
```

Na sequência, para rodar os comandos, basta conectar no bash do container e iniciar o client

```powershell
docker exec -it mongo bash
mongo
db.getName();
```
