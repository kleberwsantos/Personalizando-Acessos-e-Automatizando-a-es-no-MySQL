# Scripts SQL: Views, Usuários, Permissões e Triggers

Este repositório contém scripts SQL que demonstram a criação e uso de views, usuários, permissões e triggers em um cenário de e-commerce e uma company.

## Views

Foram criadas várias views para fornecer respostas a perguntas específicas, como o número de empregados por departamento e localidade, a lista de departamentos e seus gerentes, 
e os projetos com o maior número de empregados.

## Usuários

Foram criados dois usuários, gerente e employee, cada um com diferentes níveis de acesso ao banco de dados.

## Permissões

Foram definidas permissões específicas para os usuários gerente e employee. Por exemplo, o usuário gerente tem permissão para selecionar, inserir, atualizar e excluir
dados nas tabelas employee e departament, enquanto o usuário employee só tem permissão para selecionar dados na tabela employee.

## Triggers

Foram criados triggers que são ativados antes de um usuário excluir sua conta ou antes de um registro ser atualizado na tabela employee.
