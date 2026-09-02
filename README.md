# 👩‍💻 Evellyn dos Santos Furtado — 3°F

# 📚 API de Livros

<p align="center">
  <img src="https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png" width="180">
</p>

<p align="center">
  <b>API para gerenciamento de livros desenvolvida com FastAPI, Python e MySQL.</b>
</p>

---

## 📖 Sobre o projeto

Este projeto consiste no desenvolvimento de uma **API de Livros**, criada durante as aulas de desenvolvimento de aplicações web.

A API permite realizar operações de gerenciamento de livros, como **criar, consultar, atualizar e excluir registros**, utilizando o conceito de CRUD.

O projeto também trabalha a integração entre uma aplicação desenvolvida em Python e um banco de dados MySQL, utilizando SQLAlchemy para facilitar essa comunicação.

---

## 🎯 Objetivos

- Desenvolver uma API utilizando **FastAPI**;
- Aprender e praticar operações **CRUD**;
- Integrar a API com um banco de dados **MySQL**;
- Utilizar **SQLAlchemy** para comunicação com o banco;
- Trabalhar com requisições HTTP e rotas;
- Organizar a estrutura de um projeto backend.

---

## 📚 Dados dos livros

Cada livro possui os seguintes dados:

| Campo | Tipo | Descrição |
|---|---|---|
| `id` | `int` | Identificador único |
| `titulo` | `string` | Título do livro |
| `autor` | `string` | Nome do autor |
| `ano_publicacao` | `int` | Ano de publicação |
| `disponivel` | `boolean` | Indica se o livro está disponível |

---

## 🔌 Endpoints

| Método | Rota | Objetivo |
|:---:|---|---|
| 🟢 `POST` | `/livros` | Criar um livro |
| 🔵 `GET` | `/livros` | Listar livros |
| 🔵 `GET` | `/livros/{id}` | Consultar um livro |
| 🟡 `PUT` | `/livros/{id}` | Atualizar um livro |
| 🔴 `DELETE` | `/livros/{id}` | Excluir um livro |

---

## 🛠️ Tecnologias utilizadas

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="65">
  &nbsp;&nbsp;&nbsp;
  <img src="https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png" width="110">
  &nbsp;&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="65">
  &nbsp;&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlalchemy/sqlalchemy-original.svg" width="65">
</p>

<p align="center">
  <b>Python • FastAPI • Uvicorn • SQLAlchemy • PyMySQL • Pydantic Settings • MySQL</b>
</p>

---

## 📂 Estrutura do projeto

```text
API-LIVROS/
│
├── 📁 .venv/
│
├── 📁 app/
│   └── arquivos da aplicação
│
├── 📁 database/
│   └── arquivos relacionados ao banco de dados
│
├── 📄 .env
├── 📄 .gitignore
├── 📄 README.md
└── 📄 requirements.txt
