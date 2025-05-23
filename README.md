# 🧪 Teste Técnico - Desenvolvedor Backend PHP

## 🎯 Objetivo

Desenvolver um sistema completo para **gestão e apresentação de produtos**, composto por:

- Um **CMS administrativo** para gerenciar produtos (CRUD)
- Um **frontend público** para exibir os produtos (em cards) e detalhes individuais
- Uma **API RESTful** para integração entre frontend e backend
- Banco de dados **MySQL**
- Entrega organizada via **GitHub** com README e dump do banco

---

## 🧱 Requisitos Técnicos

### 🔙 Backend

- Linguagem: **PHP** (vanilla ou utilizando o framework Laravel)
- API RESTful com as seguintes rotas:
  - `GET /api/products` – Listar todos os produtos
  - `GET /api/products/{id}` – Exibir detalhes de um produto
  - `POST /api/products` – Criar um novo produto
  - `PUT /api/products/{id}` – Atualizar um produto
  - `DELETE /api/products/{id}` – Remover um produto
- Conectar à base de dados MySQL

---

### 🖥️ Frontend

#### 📢 Público

- Página principal com **cards de produtos**
- Página de **detalhes de produto**

#### 🔐 Administrativo (CMS)

- Tela de **login** (simples)
- Tela de **listagem** dos produtos com opções de **criar, editar e deletar**
- Formulários funcionais com feedback

#### Tecnologias Permitidas

- HTML/CSS/JS puro *(pode utilizar Tailwind ou Bootstrap)*
- OU frameworks JS como React, Vue ou Next.js

---

### 🗄️ Banco de Dados

- Utilizar **MySQL**