# metabase-pnp

## Pré-requisitos

- Java 11 ou superior 
- Docker

# INTRUÇÕES

## DADOS:

Descompactar o arquivo microdados_matriculas_2021.zip

execute:

sudo ./etl microdados_matriculas_2021.csv
CARREGANDO ARQUIVO...
LENDO 1 LINHA...
APLICANDO TRANSFORMAÇÃO...
TRANSFORMAÇÃO CONCLUIDA.

cria o arquivo:
microdados_matriculas_2021.etl.csv


## SERVIDOR

Para executar o mysql, adminer e metabase use  

cd dist
docker-compose -up

acesso localhost:3000

## CARREGAR O ARQUIVO NO MYSQL

USE A FERRAMENTA DE SUA PREFERENCIA PARA IMPORTAR O CSV NO MYSQL
