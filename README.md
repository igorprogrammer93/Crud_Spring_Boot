# 🧾 Projeto CRUD de Usuários com Spring Boot

Este projeto é uma aplicação web simples para cadastro de usuários, com funcionalidades de **criar, listar, editar e excluir**. Utiliza o framework **Spring Boot** com **Thymeleaf** para o frontend e **H2 Database** como banco de dados em memória.

---

## 🚀 Tecnologias Utilizadas

- [✔️] Java 17+
- [✔️] Spring Boot 3
- [✔️] Spring Web
- [✔️] Spring Data JPA
- [✔️] Thymeleaf (HTML dinâmico)
- [✔️] H2 Database
- [✔️] Maven

---

## 📂 Estrutura do Projeto

src/
└── main/
├── java/com/example/crud/
│ ├── CrudApplication.java
│ ├── controller/
│ │ └── UsuarioController.java
│ ├── model/
│ │ └── Usuario.java
│ └── repository/
│ └── UsuarioRepository.java
└── resources/
├── templates/
│ ├── index.html
│ └── formulario.html
└── application.properties

## ⚙️ Como Executar o Projeto

### 1. Pré-requisitos

- JDK 17 ou superior
- Maven instalado
- IDE como IntelliJ, Eclipse ou VS Code

### 2. Clonar o projeto

```bash
git clone https://github.com/seu-usuario/crud-springboot.git
cd crud-springboot

3. Rodar a aplicação

mvn spring-boot:run

Acesse no navegador:
👉 http://localhost:8080
🧑‍💻 Funcionalidades

    ✅ Criar novo usuário

    ✅ Listar todos os usuários

    ✅ Editar usuário existente

    ✅ Excluir usuário com confirmação

    ✅ Interface HTML com Thymeleaf

    ✅ H2 Console disponível para visualização dos dados


🖥️ Interface do Sistema
🏠 Tela inicial (lista de usuários)

    Tabela com todos os usuários cadastrados

    Botões de Editar e Excluir

📝 Tela de cadastro/edição

    Formulário com campos:

        Nome

        E-mail

🧪 Banco de Dados H2

Acesse:
👉 http://localhost:8080/h2-console

Credenciais:

    JDBC URL: jdbc:h2:mem:testdb

    User: sa

    Password: (em branco)


