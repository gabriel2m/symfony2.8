Symfony2.8 App
===

Software desenvolvido para entrevista de Desenvolvedor Web Full Stack (cuja vaga conquistei 😁).

Briefing
---

Crud de uma entidade abstrata com um campo string, um campo data e um campo valor.

Requisitos
---
  * Php 7.1 

  * Symfony 2.8

  * Mysql

  * Git

  * Bootstrap
  
  * Jquery

  * Web Responsivo.

Instalação
---

É extremamente simples a instalação do sistema utilizando docker, basta executar os seguintes comandos:
  1. Clone o repositório:
``` 
$ git clone https://github.com/gabriel2m/symfony2.8.git
```
  2. Entre no diretório criado:
```
$ cd symfony2.8
```
  2. Crie o arquivo de varias ambiente, a partir de .env.example, e o altere com as configurações que desejar:
```
$ cp .env.example .env
$ vim .env
```
  3. Coloque os containers em execução:
```
$ docker-compose up -d
```
  4. Instale as dependências:
```
$ docker-compose exec app composer install
```
  5. Crie as tabelas do banco de dados:
```
$ docker-compose exec app php app/console doctrine:schema:create
```
  6. Tudo pronto 🙌 Agora é so acessar via seu navegador: http://127.0.0.1

Screenshots
---
<img width="100%" src="https://github.com/gabriel2m/symfony2.8/blob/master/screenshots/index.png?raw=true" />
<img width="100%" src="https://github.com/gabriel2m/symfony2.8/blob/master/screenshots/search.png?raw=true" />
<img width="100%" src="https://github.com/gabriel2m/symfony2.8/blob/master/screenshots/confirmacao-salvar.png?raw=true" />
<img width="100%" src="https://github.com/gabriel2m/symfony2.8/blob/master/screenshots/salva.png?raw=true" />
<img width="100%" src="https://github.com/gabriel2m/symfony2.8/blob/master/screenshots/tootip.png?raw=true" />
<img width="100%" src="https://github.com/gabriel2m/symfony2.8/blob/master/screenshots/deletada.png?raw=true" />
