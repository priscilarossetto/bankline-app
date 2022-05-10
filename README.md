# Construindo um Front-end Angular de Extrato Bancário 💰

### Santander Dev Week - Java Full Stack ☕

O projeto consiste em criar uma aplicação web que se comunicará via requisições https baseadas na arquitetura REST com a [Bankline-API](https://github.com/priscilarossetto/bankline-api) desenvolvida com Springboot e disponibilzada no Heroku.

Iremos explorar recursos essenciais em um desenvolvimento utilizando Angular conforme abaixo:

* [Angular 13](https://angular.io/)
* [Angular HttpClient](https://angular.io/api/common/http/HttpClient)
* [Angular Router](https://angular.io/api/router)
* [Bootstrap 5](https://getbootstrap.com/)


## Criando o projeto com angular-cli

* Primeiramente iremos confirmar se estamos com o `node` e `npm` instalados. Neste projeto foi utilizado node v16.14.0.

~~~javascript
node --version

e

npm --version

~~~

* Depois precisaremos instalar o <b>angular-cli</b>:

~~~~javascript
npm install -g @angular/cli
~~~~

* Em seguida será possível executar os comandos angular pelo terminal:

~~~~javascript
// obtendo a versão do Angular CLI
ng --version

//gerando uma nova aplicação
ng new bankline-app

//após abrir o projeto no VSCode
ng serve -o
~~~~

* Adicionando a biblioteca do Bootstrap pelo angular-cli
~~~~javascript
1. no terminal, pare a aplicação com CTRL+C

2. ng add @ng-bootstrap/ng-bootstrap
~~~~
<b>Se ao tentar instalar o bootstrap apresentar algum erro, execute os comandos abaixo e repita o processo acima.</b>:
~~~~javascript
npm config set legacy-peer-deps true
~~~~


## Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)


# Créditos
* Aula com o passo a passo da aplicação: https://www.dio.me/dev-week/santander/bootcamps
* Instrutor da aula: [Gleyson Sampaio](https://github.com/glysns)
