# Containers de bancos de dados para desenvolvimento

## Execute os comandos abaixo antes de rodar este docker compose
```bash
docker network create bancos-net
docker network create flexdoc-net 
```

## Crie os diretórios para armazenar os volumes dos bancos de dados
```bash
# este diretório deve ficar no mesmo nível do docker-compose.yaml
mkdir -p volumes volumes/mysql volumes/postgres volumes/mongodb
```

## Comando para rodar o docker compose e baixar/executar os containers
```bash
docker-compose up -d --force-recreate
```

> Altere nomes de rede e portas caso estes recursos já estejam ocupados na sua máquina local