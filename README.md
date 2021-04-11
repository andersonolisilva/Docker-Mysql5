# Docker-Mysql5

Docker compose para implementação/disponibilização do Mysql 5.7.25 com ferramenta de administração

## Pré-requisito
- Docker instalado na máquina
- Acesso à Internet para baixar a imagem
- Crie uma pasta chamada de [dados] dentro da pasta deste projeto.

## Comando para iniciar o container
O comando abaixo deverá ser executado dentro da pasta raiz do projeto
```
docker-compose up -d
```

# Comando para iniciar o container
```
docker start sql1
```

# Comando para parar o container
```
docker stop sql1
```

## Comandos para encerrar/destruir o container
```
docker-compose down
```

## Instruções para acesso
- Para acessar a ferramenta administrativa utilize o link http://localhost:8070 e preencha os dados para acesso
```
Sistema: MySQL
Servidor: mysqlsrv
Usuário: root
Senha: Password_123
Base de dados: <<Opcional: pode deixar em branco para ver todos os bancos de dados ao acessar>>
```
Créditos pela ferramenta administrativa [https://www.adminer.org/en/donation/]


## O que terá ao final do processo
- Servidor Mysql habilitado para desenvolvimento de sistemas
- Ferramenta Web para adminstração do seu banco de dados