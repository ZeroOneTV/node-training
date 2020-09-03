## Node-Training
###### Um repositório para treinos relacionados ao Node..JS v12.18

Estarei adicionando neste repositório algumas APIs apenas com finalidade de estudos, sempre que possível comentando o código para que fique de fácil entendimento tanto para leigos quanto para pessoas de conhecimento avançado.

*Em caso de sugestões de melhorias e críticas, estarei à disposição.*

------------

### Os comandos utilizados para as dependências

`$ npm i koa`
> ######Como Servidor usaremos o Koa.

`$ npm i koa-router`
>  ######Responsável pelo gerenciamento de rotas.

`$ npm i @koa/cors`
>  ######Responsável por liberar os acessos para determinados endereços de IP.

`$ npm i koa-bodyparser`
>  ######Responsável por converter a requisição do usuário em Json e converter para que possa ser validado dos dados.

`$ npm i boom`
>  ######Responsável por lidar com o tratamento de erros.

`$ npm i fastest-validator`
>  ######Responsável por validar os parâmetros que estamos recebendo no servidor.

`$ npm i sequelize` e `$ npm i sequelize-cli` 
>  ######Responsável por gerenciar o acesso,envio e recebimento de dados do Banco de Dados utilizado.

`$ npm i sqlite3`
> ##### No caso específico do estudo, estarei utilizando SQLITE 3, porém pode-se utilizar qualquer SGBD que queira, apenas fazendo as modificações no arquivo de gerenciamento das requisições para o banco de dados. 

`$ npm i -D nodemon `
>  ######Dependência apenas para Desenvolvimento. Nodemon fica responsável para atualizar as alterações realizadas durante o desenvolvimento, sendo assim, não necessário ficar reiniciando o servidor a cada alteração.
