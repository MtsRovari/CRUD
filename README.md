## Descrição

Este é um projeto de aplicação web, consiste na criação CRUD de usuários e livros. Com controle de usuários e banco de dados integrado.
O projeto foi criado a partir do padrão MVC (Model, View, Controller).

## Recursos utilizados

PHP | HTML | CSS | e banco de dados MYSQL.

## Ferramentas utilizadas

* Framework FuelPHP;
* Editor de códigos e editor visual Sublime Text 3.0;
* Servidor XAMPP;
* phpmyadmin para administração do MYSQL;
* GitBash como terminal de comandos.

## Project Structure

### Pasta Model

É responsável pela leitura e escrita dos dados e das validações da aplicação.
* A pasta model e seus derivados são encontrados em Simple-CRUD > fuel > app > classes > model. 

### Pasta Controller

É responsável por receber todas as requisições do usuário, e cada metodo action, é uma página, e controla qual model usar e qual view exibir para o usuário.
* A pasta controller é encontrada em Simple-CRUD > fuel > app > classes > controller.

### Pasta View

É responsavel em fazer a exibição dos dados apenas, uma camada de interação com o usuário.
* A pasta view é encontrada em Simple-CRUD > fuel > app > views (dividida em auth, books e users).

### Arquivo database

* O arquivo db.php é encontrado em Simple-CRUD > fuel > app > config > development > db.php

### Para testar o projeto basta apenas 

* Clonar ou fazer o download do repositório na sua máquina;
* composer install (permissions/setup do projeto);
* Configurar o banco de dados no arquivo db.php;
* php oil r migrate para criar as tabelas e estrutura do banco de dados.

