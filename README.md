# astrus-backoffice

Projeto de backoffice que inclui portal web, API e banco de dados

## Estrutura do projeto

```txt
api/             # Pasta com projeto de API em Laravel
db/              # Pasta com arquivos de configuração para o banco de dados (MySQL) 
web/             # Pasta com projeto de portal web em React
compose-dev.yml  # Docker compose para o ambiente de desenvolvimento
compose-prd.yml  # Docker compose para o ambiente de produção
Dockerfile.api   # Dockerfile para uso da API 
Dockerfile.web   # Dockerfile para uso do portal web
README.md        # Você está aqui :)
```

## Utilização

> [!IMPORTANT]
> Este projeto utiliza docker. Verifique se o docker está instalado na sua máquina, se não, [instale-o aqui](https://www.docker.com/).

### Desenvolvimento

```bash
docker compose -f compose-dev.yml up -d
```

### Produção

```bash
docker compose -f compose-prd.yml up -d
```
