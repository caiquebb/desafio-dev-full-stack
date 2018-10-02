# Desafio Desenvolvedor WEB PHP FULL-STACK.

## Introdução

Este desafio tem a finalidade de qualificar você que quer ser um integrante do time de desenvolvimento da AGV, como um Desenvolvedor WEB PHP FULL-STACK.

## Requisitos

Você terá que desenvolver um sistema de blog onde o mesmo será composto por dois projetos utilizando o framework PHP Laravel.

### Backend

O Primeiro projeto será responsável pelo backend do sistema e deverá seguir as seguintes premissas:

* API RESTful
* Conexão com Banco de dados relacional

### Frontend

O Segundo projeto será responsável pelo frontend do sistema e deverá seguir as seguintes premissas:

* Responsivo
* Integrado com a API.

### Entrega

Os dois projetos devem estar disponíveis no gitlab na conta de seu usuário. Ao entrar na página de seu projeto exibir o README explicando o que é cada projeto e com um passo a passo para a instalação do mesmo.

## User Stories

### MVP

* Eu como autor gostaria de publicar um artigo no blog com título, imagem e descrição.
* Eu como autor gostaria de editar um artigo já publicado.
* Eu como autor gostaria de excluir um artigo.
* Eu como autor gostaria de uma área exclusiva com autenticação para publicar, editar ou excluir um artigo.
* Eu como usuário gostaria que a página inicial exiba os últimos artigos publicados em ordem decrescente com a imagem, título e um resumo do artigo.
* eu como usuário gostaria que quando clicar na imagem título ou resumo, ser redirecionado para uma página que contenha o artigo completo e seus comentários.
* Eu como usuário gostaria de publicar um comentário anônimo (sem login).

### Backlog

* Eu como usuário gostaria de publicar um comentário (com login).
* Eu como autor gostaria de excluir um comentário na página de edição do artigo.
* Eu como autor gostaria de exibir as datas de criação do artigo e a data da última atualização caso o mesmo for editado.
* Eu como usuário gostaria de realizar uma pesquisa para filtrar os artigos publicados.
* Eu como autor gostaria de definir uma categoria para o meu artigo.
* Eu como usuário gostaria de exibir os artigos de uma determinada categoria.
* Eu como autor gostaria de incluir tags em um artigo.
* Eu como usuário gostaria de exibir artigos de uma determinada tag.

## Diferenciais

* Autenticação com oAuth2 na API (Laravel passport).
* Utilizar Vue.JS no Frontend.
* App mobile hibrido integrado com a API.