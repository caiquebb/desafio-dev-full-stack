# Desafion desenvolvedor web php full-stack.

## Introdução

Este desafio tem a finalidade de qualificar você que ser um integrante do time de desenvolvimento da AGV, como um desenvolvedor web Full-Stack.

## Requisitos

Você tera que desenvolver um sistema de blog onde o mesmo será composto por dois projetos utilizando o framework PHP Laravel.

### Backend

O Primeiro projeto será responsável pelo backend do sistema e devera seguir as seguintes premissas:

* API RESTful
* Conexão com Banco de dados relacional

### Frontend

O Segundo projeto será responsável pelo frontend do sistema e devera seguir as seguintes premissas:

* Responsivo
* Integrado com a API.

## User Stories

### MVP

* Eu como autor gostaria de publicar um artigo no blog com titulo, imagem e descricao.
* Eu como autor gostaria de editar um artigo já publicado.
* Eu como autor gostaria de excluir um artigo.
* Eu como autor gotaria de uma area exclusiva com autenticação para publicar, editar ou excluir um artigo.
* Eu como usuário gostaria que a pagina inicial exiba os ultimos artigos publicados em order decrescente com a imagem, titulo e um resumo do artigo.
* eu como usuário gostaria que quando clicar na imagem titulo ou resumo, ser redirecionado para uma página que contenha o artigo completo e seus comentários.
* Eu como usuário gostaria de publicar um comentario anonimo (sem login).

### Backlog

* Eu como usuário gostaria de publicar um comentário (com login).
* Eu como autor gostaria de excluir um comentário na página de edição do artigo.
* Eu como autor gostaria de exibir as datas de criação do artigo e a data da ultima atualização caso o mesmo for editado.
* Eu como usuário gostaria de realizar uma pesquisa para filtrar os artigos publicados.
* Eu como autor gostaria de definir uma categoria para o meu artigo.
* Eu como usuário gostaria de exibir os artigos de uma determinada categoria.
* Eu como autor gostaria de incluir tags em um artigo.
* Eu como usuário gostaria de exibir artigos de uma determinada tag.

## Diferenciais

* Autenticação com oAuth2 na API (Laravel passport).
* Utiliza Vue.JS no Frontent.
