# Banco de dados

O banco de dados é uma instância MySQL que roda em um container Docker. A configuração do banco de dados é feita através de arquivos de configuração que estão na pasta `db/`.

## Configuração do ambiente

Faça download dos arquivos de segredos do banco de dados que foram enviados por email.
    - Os arquivos .json devem estar contidos em uma pasta chamada `secrets/` na raiz do projeto.

## Utilização

Para subir o banco de dados, execute o seguinte comando:

```bash
docker compose up -d
```

Para acessar o shell do MySQL, execute o seguinte comando:

```bash
docker exec -it astrus-mysql mysql -u root -p
```

Ao ser solicitado pela senha, digite a senha que está presente no arquivo `secrets/root_password.json`.