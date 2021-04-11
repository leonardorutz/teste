# Apresente suas habilidades com o teste abaixo:

A necessidade é desenvolver uma API RESTFul para gerenciamento de pedidos de uma papelaria utilizando o framework Laravel

## Instruções para entrega

* Versione, com git, e hospede seu código em algum serviço de sua preferência: github, bitbucket, gitlab ou outro.
* Crie um README com instruções claras sobre como executar sua obra.
* Envie um email com o link do seu repositório para leonardo@rutztecnologia.com.br
* Dúvidas podem ser enviadas para o mesmo email acima.

## Sobre o projeto

A API Restful deve contemplar os módulos **Cliente**, **Produtos** e **Pedido**, sendo que cada um devera conter  endpoints **CRUDL**.

As tabelas devem conter as seguintes informações:

* **Cliente** `nome, email, telefone, data de nascimento, endereço, complemento, bairro, cep, data de cadastro`;
* **Produto** `nome, preço, foto`;
* **Pedido** `código do cliente, código(s) do produto, data da criação`;

## Requisitos

* Não devem existir dois clientes com o mesmo email.
* O produto deve possuir foto.
* Os dados devem ser validados.
* O sistema deve conter uma série de tipos de produtos já definidos.
* O pedido deve contemplar N produtos.
* O cliente pode contemplar N pedidos.
* Os registros devem conter a funcionalidade de soft deleting.
* Padronização PSR
* Nomenclatura de classes, métodos e rotas no padrão americano.
* Não é necessário utilizar padrão de autenticação (ex. OAuth) para consumir a API

## Desejável
* Testes unitários.
* Dockerizar a aplicação

## Critérios de avaliação

* Profundidade do conhecimento e utilização das funcionalidades do framework.
* Organização do código.
* Padronização PSR
* Fidelidade aos requisitos solicitados.
* Design Patterns utilizados
