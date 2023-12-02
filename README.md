# Laravel Product API

Bem-vindo à documentação da API Laravel para gerenciamento de produtos. Esta API permite a realização das operações básicas CRUD (Create, Read, Update, Delete) em produtos.

## Índice

1. [Requisitos](#requisitos)
2. [Instalação](#instalação)
3. [Configuração](#configuração)
4. [Endpoints](#endpoints)
    - [Listar Produtos](#listar-produtos)
    - [Criar Produto](#criar-produto)
    - [Atualizar Produto](#atualizar-produto)
    - [Excluir Produto](#excluir-produto)
6. [Considerações Finais](#considerações-finais)

## Requisitos

- PHP >= 8.0
- Composer
- Laravel >= 10.x
- Banco de dados MySQL ou SQLite

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git

2. Instale as dependências do Composer:
    ```bash
    composer install

3. Copie o arquivo .env.example para .env e configure o banco de dados.

4. Execute as migrações e os seeders:
    ```bash
    php artisan migrate --seed

## Configuração

A configuração da API é feita principalmente no arquivo .env. Certifique-se de configurar corretamente o banco de dados, cache e outras configurações necessárias.

## Endpoints

Listar Produtos
Endpoint: GET /api/products

Retorna a lista de todos os produtos.

Criar Produto
Endpoint: POST /api/products

Cria um novo produto com base nos dados fornecidos no corpo da requisição.

Atualizar Produto
Endpoint: PUT /api/products/{id}

Atualiza os detalhes de um produto específico com base no ID e nos dados fornecidos no corpo da requisição.

Excluir Produto
Endpoint: DELETE /api/products/{id}

Exclui um produto específico com base no ID.

## Considerações finais
Esta é uma API simples para CRUD de produtos em Laravel. Sinta-se à vontade para contribuir, relatar problemas ou propor melhorias.
