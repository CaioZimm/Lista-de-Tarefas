# ✅ Lista de Tarefas — Aplicação Full Stack

🧭 **Projeto:** Lista de Tarefas (To-Do List)  
💡 **Objetivo:** Criar uma aplicação completa para gerenciamento de tarefas, permitindo cadastrar, listar, editar e excluir itens de forma simples e intuitiva.  
🧑‍💻 **Tecnologias:** Java (Spring Boot) + Vue.js

---

## 🚀 Sobre o Projeto

Este projeto foi desenvolvido como parte da disciplina de **Desenvolvimento Full Stack**, com o intuito de aplicar os conceitos de integração entre **frontend** e **backend**, utilizando o padrão REST para comunicação entre cliente e servidor.

A aplicação possui uma interface simples e intuitiva para o usuário gerenciar suas tarefas, enquanto o backend fornece toda a base de dados e lógica de negócio.

---

## 🧩 Estrutura do Projeto

```
listadetarefas_06/
├── backend/         # API REST desenvolvida em Java Spring Boot
│   ├── src/         # Código-fonte da aplicação
│   └── pom.xml      # Gerenciador de dependências Maven
│
├── frontend/        # Interface do usuário feita em Vue.js
│   ├── src/         # Componentes, views e rotas
│   └── package.json # Dependências e scripts do projeto
│
└── README.md        # Documentação do projeto
```

---

## ⚙️ Funcionalidades

- 📝 **Cadastrar Tarefa** — Criação de novas tarefas com título e descrição.  
- 📋 **Listar Tarefas** — Exibição de todas as tarefas cadastradas.  
- ✏️ **Editar Tarefa** — Alteração de informações de uma tarefa existente.  
- ❌ **Excluir Tarefa** — Remoção de tarefas concluídas ou indesejadas.  
- 🔄 **Integração Total** — Comunicação entre frontend e backend via API REST.

---

## 🧠 Conceitos Aplicados

- Arquitetura **Cliente-Servidor**
- API RESTful com **Spring Boot**
- Consumo de API com **Axios** no Vue.js
- Padrão **CRUD (Create, Read, Update, Delete)**
- Separação de camadas e responsabilidades
- Versionamento de código com **Git**

---

## 🛠️ Tecnologias Utilizadas

### 🔹 Backend
- Java 17  
- Spring Boot  
- Spring Web  
- Spring Data JPA  
- H2 Database (banco em memória)  
- Maven

### 🔹 Frontend
- Vue.js  
- Axios  
- HTML5, CSS3 e JavaScript  
- Node.js

---

## 🧪 Como Executar o Projeto

### 🔸 1. Clonar o Repositório
```bash
git clone https://github.com/seu-usuario/listadetarefas_06.git
cd listadetarefas_06
```

### 🔸 2. Executar o Backend
```bash
cd backend
mvn spring-boot:run
```
> O servidor iniciará em: `http://localhost:8080`

### 🔸 3. Executar o Frontend
```bash
cd frontend
npm install
npm run serve
```
> A interface estará disponível em: `http://localhost:5173` ou similar.

---

## 📚 Aprendizados

Durante o desenvolvimento deste projeto, foi possível consolidar conhecimentos sobre:
- Integração entre frontend e backend;
- Implementação de APIs REST;
- Manipulação de dados via requisições HTTP;
- Organização e modularização de código em aplicações full stack.

---

## 👨‍💻 Autor

**Caio Claudino Venancio**  
Estudante de Análise e Desenvolvimento de Sistemas — Fema 

---

## 📄 Licença

Este projeto é de uso educacional e livre para estudo e melhorias.
