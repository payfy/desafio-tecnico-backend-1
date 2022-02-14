# Desafio Técnico Payfy
Nesse desafio, você vai ter que criar uma API REST para controle de usuarios no sistema

### Funcionalidades obrigatórias
* criar o projeto em um repositorio aonde o examinador possa acessar(publico **ou** adicionar o examinador como contribuidor do repo)
* uma rota para criar um usuario, deve ser salvo no banco de dados
* rota para criar configuração de usuario, deve ser salvo em uma tabela separada do usuario
* permitir criar apenar usuarios com 18 anos ou mais
* rota de listar usuarios

### Modelo de dados
#### Usuario
| Nome | Tipo |
|----|-----|
|nome| String|
|idade| Inteiro|
|email| String|


#### Configuração de usuario
| Nome | Tipo |
|----|-----|
|tema| "dark", "medium" ou "light"|
|notificações por email| Boleano|


### Funcionalidades não obrigatórias, porem legal de se ter
* arquivo de testes
* documentação das rotas
* ser em elixir/phoenix
* autenticação/permissão de criação apenas para usuarios administradores

### Observações
* Qualquer duvida você pode ou perguntar para quem lhe passou o desafio, ou assumir a resposta e documentar todas suas assunções no read-me do seu projeto

### Critérios de avaliação
* código está bem estruturado
* código faz o uso correto de Design Patterns
* sabe explicar o motivo das decisões de implementações
* o projeto realiza todas as funcionalidades básicas requeridas
* o README do projeto tem todos os detalhes que precisam para rodar o projeto em outro computador

### Sugestão de Estudo
* [Clean Code - Guia e Exemplos](https://balta.io/artigos/clean-code)
* [Elixir School - Lições sobre a linguagem de programação Elixir](https://elixirschool.com/pt/)
