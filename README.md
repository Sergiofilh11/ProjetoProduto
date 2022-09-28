# Projeto Cadastro de Produto
CRUD with Java Swing

### 📋 Pré-requisito

- Criar banco de dados e as tabelas abaixo.
```sh
CREATE DATABASE db_pedido
```

```sh
CREATE TABLE produto (
  id int not null primary key auto_increment,
  descricao varchar(60) not null,
  data_cadastro timestamp default current_timestamp )
```

```sh
CREATE TABLE estoque (
  produtoID int NOT NULL PRIMARY KEY,
  quantidade int )
```
