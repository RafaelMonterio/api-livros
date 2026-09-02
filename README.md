# 📚 API de Livros — Rafael Vasconcelos Monterio

<p align="center">
  <img src="https://img.shields.io/badge/Projeto-SW--II-red?style=for-the-badge" alt="Projeto SW-II">
  <img src="https://img.shields.io/badge/Python-red?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-red?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/MySQL-red?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
</p>

<h3 align="center">🧑‍💻 Sistemas Web II · Projeto Prático</h3>

<p align="center">
  <strong>Do banco de dados ao Front End, construindo uma API passo a passo.</strong>
</p>

---

## 👨‍💻 Sobre o projeto

Este repositório pertence a **Rafael Vasconcelos Monterio** e foi desenvolvido como parte das atividades da disciplina de **Sistemas Web II (SW-II)**.

O objetivo deste projeto é colocar em prática conceitos de desenvolvimento **Back End, APIs, bancos de dados e Front End**, acompanhando cada etapa do desenvolvimento de uma aplicação web.

A aplicação será construída gradualmente, começando pela configuração do ambiente e conexão com o banco de dados, passando pela criação da API e do CRUD, até chegar à interface web.

> 🔴 **Projeto desenvolvido de forma incremental:** cada etapa representa uma parte da evolução da aplicação.

---

## 🎯 O desafio

Construir uma aplicação web para **gerenciamento de livros**, utilizando uma API desenvolvida em **Python + FastAPI**, conectada a um banco de dados **MySQL** e posteriormente integrada a uma interface desenvolvida com **HTML, CSS e JavaScript**.

Cada livro possuirá as seguintes informações:

| Campo            | Descrição                         |
| ---------------- | --------------------------------- |
| `id`             | Identificador único do livro      |
| `titulo`         | Título do livro                   |
| `autor`          | Autor do livro                    |
| `ano_publicacao` | Ano em que o livro foi publicado  |
| `disponivel`     | Indica se o livro está disponível |

---

## 🔄 CRUD da aplicação

A aplicação deverá implementar as quatro operações fundamentais de um sistema de gerenciamento de dados:

| Operação      | Método   | Função                    |
| ------------- | -------- | ------------------------- |
| 🟢 **Create** | `POST`   | Cadastrar livros          |
| 🔵 **Read**   | `GET`    | Listar e consultar livros |
| 🟠 **Update** | `PUT`    | Atualizar informações     |
| 🔴 **Delete** | `DELETE` | Excluir livros            |

---

## 🚀 Objetivos

Ao longo do projeto, os principais objetivos são:

* 🐍 Desenvolver uma API utilizando **Python e FastAPI**;
* 🔗 Criar e utilizar rotas HTTP;
* 🗄️ Conectar uma aplicação Python ao **MySQL**;
* 🛠️ Utilizar **XAMPP e phpMyAdmin**;
* 📦 Trabalhar com **SQLAlchemy**;
* 📝 Criar modelos e schemas;
* ✅ Validar informações recebidas pela API;
* ⚠️ Trabalhar com erros HTTP;
* 🌐 Desenvolver uma interface utilizando HTML, CSS e JavaScript;
* 🔄 Consumir uma API através do `fetch`;
* 💻 Utilizar o VS Code durante o desenvolvimento;
* 📁 Utilizar Git e GitHub para controlar a evolução do projeto.

---

# 🧩 Jornada de desenvolvimento

O projeto será desenvolvido em **4 etapas**, seguindo a sequência proposta para a atividade.

---

## 🔴 Etapa 1 · Fundação

**Objetivo:** preparar toda a estrutura necessária para iniciar o projeto.

Nesta etapa serão trabalhados:

* Configuração do ambiente;
* Criação do ambiente virtual;
* Instalação das dependências;
* Configuração do FastAPI;
* Configuração do MySQL;
* Criação do banco `biblioteca_db`;
* Conexão entre Python e MySQL;
* Configuração do XAMPP;
* Utilização do phpMyAdmin;
* Primeira rota da aplicação.

📖 **Guia:** `01-fundacao-fastapi-mysql.md`

---

## 🔴 Etapa 2 · Modelo e consultas

**Objetivo:** começar a trabalhar efetivamente com os livros.

Nesta etapa serão desenvolvidos:

* Modelo `Livro`;
* Schemas da aplicação;
* Sessão do banco de dados;
* Criação de livros;
* Listagem de livros;
* Rota `POST`;
* Rota `GET`;
* Testes das primeiras operações.

📖 **Guia:** `02-modelo-post-get.md`

---

## 🔴 Etapa 3 · CRUD completo

**Objetivo:** finalizar as operações da API.

Serão implementadas:

* Rota `PUT`;
* Rota `DELETE`;
* Atualização de livros;
* Exclusão de livros;
* Tratamento de erros;
* Validações;
* Testes completos do CRUD.

📖 **Guia:** `03-put-delete-crud.md`

---

## 🔴 Etapa 4 · Front End

**Objetivo:** criar uma interface para utilizar a API através do navegador.

Nesta etapa serão desenvolvidos:

* Interface HTML;
* Estilização com CSS;
* Funcionalidades com JavaScript;
* Cadastro de livros;
* Listagem de livros;
* Edição de livros;
* Exclusão de livros;
* Integração com a API através do `fetch`.

📖 **Guia:** `04-frontend-html-css-js.md`

---

# 🛠️ Tecnologias utilizadas

### Back End

![Python](https://img.shields.io/badge/Python-red?style=flat-square\&logo=python\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-red?style=flat-square\&logo=fastapi\&logoColor=white)
![Uvicorn](https://img.shields.io/badge/Uvicorn-red?style=flat-square)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-red?style=flat-square)
![PyMySQL](https://img.shields.io/badge/PyMySQL-red?style=flat-square)

### Banco de dados

![MySQL](https://img.shields.io/badge/MySQL-red?style=flat-square\&logo=mysql\&logoColor=white)
![XAMPP](https://img.shields.io/badge/XAMPP-red?style=flat-square\&logo=apache\&logoColor=white)
![phpMyAdmin](https://img.shields.io/badge/phpMyAdmin-red?style=flat-square\&logo=php\&logoColor=white)

### Front End

![HTML5](https://img.shields.io/badge/HTML5-red?style=flat-square\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-red?style=flat-square\&logo=css3\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-red?style=flat-square\&logo=javascript\&logoColor=white)

### Ferramentas

![VS Code](https://img.shields.io/badge/VS%20Code-red?style=flat-square\&logo=visualstudiocode\&logoColor=white)
![Git](https://img.shields.io/badge/Git-red?style=flat-square\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-red?style=flat-square\&logo=github\&logoColor=white)

---

## 🗄️ Banco de dados

O banco utilizado no projeto será:

```text
biblioteca_db
```

A administração do banco será realizada através do:

```text
XAMPP → MySQL → phpMyAdmin
```

O arquivo SQL do banco será mantido no próprio repositório para facilitar a reconstrução do ambiente durante o desenvolvimento.

📁 Estrutura esperada:

```text
database/
└── biblioteca_db.sql
```

> ⚠️ O arquivo `.env` **não deve ser enviado para o GitHub**, pois pode conter informações de acesso ao banco de dados.

---

# 📂 Estrutura do projeto

A estrutura será construída gradualmente durante as etapas:

```text
API-DE-LIVROS/
│
├── database/
│   └── biblioteca_db.sql
│
├── .env
├── .gitignore
├── main.py
├── database.py
├── models.py
├── schemas.py
├── requirements.txt
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── 01-fundacao-fastapi-mysql.md
├── 02-modelo-post-get.md
├── 03-put-delete-crud.md
├── 04-frontend-html-css-js.md
│
└── README.md
```

---

# 📅 Cronograma

O projeto será desenvolvido seguindo as etapas estabelecidas para a atividade:

| Etapa | Data       | Conteúdo              |
| ----- | ---------- | --------------------- |
| 🔴 1  | 02/09/2026 | Ambiente e conexão    |
| 🔴 2  | 09/09/2026 | Modelo e `POST`/`GET` |
| 🔴 3  | 16/09/2026 | `PUT`/`DELETE` e CRUD |
| 🔴 4  | 23/09/2026 | Interface Web         |

> 📌 O desenvolvimento seguirá a sequência das aulas, registrando a evolução do projeto através dos commits no GitHub.

---

# 🔄 Controle de versão

O **GitHub** será utilizado para armazenar o histórico de desenvolvimento do projeto.

Ao final de cada etapa, será realizado:

1. Conferência dos arquivos;
2. Verificação das alterações;
3. Criação do commit;
4. Envio das alterações para o GitHub.

Exemplo:

```bash
git add .
git commit -m "Etapa 1 - Fundação FastAPI e MySQL"
git push
```

---

# 🧱 Padrão de código

O projeto seguirá uma abordagem simples e didática, priorizando código fácil de entender e manter.

Alguns exemplos de nomes utilizados:

```text
Livro
LivroCriacao
LivroResposta

criar_livro()
listar_livros()
atualizar_livro()
excluir_livro()
```

A intenção é manter a lógica explícita, evitando abstrações desnecessárias durante o aprendizado.

---

# 🧪 Testes

Durante o desenvolvimento, as rotas da API serão testadas para verificar:

* ✅ Cadastro de livros;
* ✅ Listagem de livros;
* ✅ Consulta de informações;
* ✅ Atualização de registros;
* ✅ Exclusão de registros;
* ✅ Validação dos dados;
* ✅ Tratamento de erros;
* ✅ Comunicação entre Front End, API e banco de dados.

---

# 📈 Evolução do projeto

Este repositório também servirá como um registro da minha evolução durante o desenvolvimento.

```text
Banco de Dados
      ↓
FastAPI
      ↓
Modelos e Schemas
      ↓
CRUD
      ↓
Testes
      ↓
Front End
      ↓
Aplicação Web
```

A proposta é entender não apenas como escrever o código, mas também **como as diferentes partes de uma aplicação web se conectam**.

---

# 🏁 Resultado esperado

Ao concluir as quatro etapas, o projeto deverá possuir:

* 🔴 API desenvolvida com FastAPI;
* 🔴 Banco de dados MySQL;
* 🔴 Integração Python + MySQL;
* 🔴 CRUD completo;
* 🔴 Validação de dados;
* 🔴 Tratamento de erros;
* 🔴 Interface Web;
* 🔴 Comunicação entre Front End e API;
* 🔴 Projeto organizado no GitHub.

---

## 👨‍💻 Desenvolvedor

**Rafael Vasconcelos Monterio**

🎓 Estudante de **Técnico em Informática para Internet**

📚 Projeto desenvolvido para a disciplina de **Sistemas Web II — SW-II**

---

<p align="center">
  <strong>🔴 Rafael Vasconcelos Monterio</strong><br>
  <sub>Aprendendo. Desenvolvendo. Evoluindo.</sub>
</p>
