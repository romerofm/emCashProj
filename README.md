
# Dicas para inicializar o projeto

* Este projeto utiliza Laravel Lumen

* Voce precisará do composer, docker e docker compose instalados 
* you will need composer, docker and docker compose installed

* Voce deve rodar o comando 'composer install --ignore-platform-reqs' primeiramente depois de clonar o repositório 
* You must run the command 'composer install --ignore-platform-reqs' as the first step after you clone the project

* Após inicializado todos os containers você terá acesso a alguns arquivos .sh 
* after properly start the containers you will have access to some .sh files

 - composer-install.sh
    - Este arquivo irá importar todas as bibliotecas necessárias para o funcionamento apropriado do projeto
    - This file will import all the necessary libraries for the proper functioning of the project

 - migrations.sh
    - este arquivo irá criar e popular o banco de dados com um registro exemplo
    - This file will create the database and seed with an example register

 - run-tests.sh
    - ste arquivo executa a pilha de testes automatizados
    - This file executes the automated tests stack

## Portas

 - api: 8000
 - phpmyadmin: 8080
 - swagger: 82



## .csv

* O `.csv` se encontra dentro da pasta `example/`

* Copie este arquivo e use como base



