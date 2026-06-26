# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Criar uma API REST simples com FastAPI para gerenciar uma coleção de itens, praticando rotas, validação de requisições e respostas em JSON.

## 📝 Tasks

### 🛠️ Configurar a aplicação

#### Description
Criar um projeto básico com FastAPI e expor um endpoint de verificação de saúde.

#### Requirements
O programa completo deve:

- Instalar o FastAPI e o Uvicorn.
- Criar uma instância da aplicação com `FastAPI()`.
- Implementar um endpoint `GET /health` que retorne `{"status": "ok"}`.

### 🛠️ Implementar rotas CRUD

#### Description
Adicionar endpoints para listar, criar, atualizar e excluir itens armazenados em memória.

#### Requirements
O programa completo deve:

- Criar um modelo de dados com `pydantic` para um item.
- Implementar `GET /items` para listar itens.
- Implementar `POST /items` para adicionar um novo item.
- Implementar `PUT /items/{item_id}` para atualizar um item.
- Implementar `DELETE /items/{item_id}` para remover um item.

### 🛠️ Adicionar validação e documentação

#### Description
Adicionar validação de requisições e verificar a documentação automática gerada pelo FastAPI.

#### Requirements
O programa completo deve:

- Validar campos obrigatórios e tipos de dados no corpo das requisições.
- Retornar mensagens claras para entradas inválidas.
- Confirmar que a documentação interativa em `/docs` esteja disponível.
