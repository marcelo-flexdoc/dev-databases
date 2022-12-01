# Containers de bancos de dados para desenvolvimento

## Execute os comandos abaixo antes de rodar este docker compose
```bash
docker network create bancos-net
docker network create flexdoc-net 
```

## Comando para rodar o docker compose e baixar/executar os containers
```bash
docker-compose up -d --force-recreate
```

> Altere nomes de rede e portas caso estes recursos já estejam ocupados na sua máquina local