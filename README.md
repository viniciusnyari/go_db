# Acessando banco de dados com Go

## Subindo Docker
- docker-compose up -d

## Acessando o MySQL no container
- docker-compose exec mysql bash
- mysql -uroot -p goexpert

## Criar tabela
- create table products (id varchar(255), name varchar(80), price decimal(10,2), primary key(id));	

## Comandos diversos MySQL
- show tables;
- describe products;
- select * from products

### Executando GO
- go run main.go;