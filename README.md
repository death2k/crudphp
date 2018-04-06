Projeto CRUD em PHP - Bootstrap & PDO - Flávio Ribeiro
=======================================================

Desenvolvimento de um pequeno projeto CRUD (agenda de contatos) utilizando o acesso a banco de dados com o MySQL e linguagem PHP.

##Assuntos abordados no desenvolvimento do projeto:

- Acesso a banco de dados com o MySql
- Otimização da conexão com o banco de dados através do PDO (PHP Data Object)
- Uso de linguagens, como: JavaScript e CSS
- Uso do framework Bootstrap para realização de um layout responsivo para o projeto.

----

Criando a tabela no banco

* Criar o Banco - "crudphp"

* CREATE TABLE contato (
id INT(6) UNSIGNED AUTO_INCREMENT PRIMARY KEY,
nome VARCHAR(30) NOT NULL,
endereco VARCHAR(30) NOT NULL,
telefone VARCHAR(50),
email VARCHAR(50),
sexo VARCHAR(50)
) 

-----

