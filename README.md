# Agrotech API

## 1. Introdução

Este documento especifica os requisitos para a implementação de uma API para um sistema de gestão agro (fazendas). O objetivo é permitir a criação, leitura, atualização e exclusão (CRUD) de dados relacionados às operações agrícolas, incluindo fazendas e cultivos.

## 2. Escopo

A API fornecerá serviços para operações CRUD sobre os seguintes recursos principais:

    Fazendas
    Cultivos (Ex: Milho, Soja)

Cada recurso será identificado por um identificador único (ID) e estará disponível em uma tabela.

## 3. Requisitos
### Recursos Principais

1. Fazenda
- Criar Fazenda: A API deve permitir a criação de uma nova fazenda com detalhes como nome, localização (Cidade e Estado) e  área total em m².
- Listar Fazendas: A API deve fornecer uma lista paginada de todas as fazendas cadastradas.
- Atualizar Fazenda: A API deve permitir a atualização de informações de uma fazenda existente.
- Excluir Fazenda: A API deve permitir a exclusão de uma fazenda.

2. Cultivo
- Criar Cultivo: A API deve permitir a adição de um novo cultivo associado a uma fazenda específica, incluindo detalhes como tipo de cultura, área plantada e status de desenvolvimento.
- Listar Cultivos: A API deve permitir listar os cultivos de uma fazenda específica.
- Atualizar Cultivo: A API deve permitir a atualização de um cultivo existente.
- Excluir Cultivo: A API deve permitir a exclusão de um cultivo.

## 4. Palavras chaves e links úteis
1. CRUD
- C = Create
- R = Read
- U = Update
- D = Delete

CRUD nada mais é que um sistema capaz de Criar, ler editar e deletar. 

https://developer.mozilla.org/pt-BR/docs/Glossary/CRUD

2. API

API em resumo é o sistema resopnsável por definir e gerenciar as regras de negócio para interagir com uma base de dados.

https://developer.mozilla.org/pt-BR/docs/Glossary/API

https://dev.to/newren/api-crud-mvc-o-que-sao-todas-essas-siglas-no2

## 5. Tecnologias propostas
1. Java
2. Bibliotecas Spring
3. Qualquer banco de dados relacional (Ex: MariaDB, MySQL, Postgres)
4. Qualquer outra biblioteca e tecnologia que achar necessário pra dar suporte ao desenvolvimento.

