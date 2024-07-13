# Português
# **CRUD de Usuários Fullstack**
Este projeto é um sistema simples de CRUD (Create, Read, Update, Delete) de usuários, desenvolvido como um exercício prático de integração entre tecnologias de Frontend e Backend. A aplicação foi construída utilizando Java e Spring Boot no Backend, MySQL como banco de dados e React.js no Frontend.

## Tecnologias Utilizadas
- Backend:
  - Java
  - Spring Boot
  - JPA/Hibernate
  - MySQL
  - API REST

- Frontend:
  - React.js
  - Axios (para requisições HTTP)
  - Bootstrap (para estilização)

## Funcionalidades
- Adicionar Usuário: Permite a criação de um novo usuário com nome, nome de usuário e email.
- Listar Usuários: Exibe uma lista de todos os usuários cadastrados.
- Atualizar Usuário: Permite a edição das informações de um usuário existente.
- Deletar Usuário: Permite a remoção de um usuário do sistema.

## Como Executar o Projeto
### Pré-requisitos
- Java 11+
- Maven
- Node.js
- MySQL

### Backend
1. Clone o repositório:
`git clone https://github.com/seu-usuario/seu-repositorio.git`

2. Navegue até o diretório do projeto backend:
`cd seu-repositorio/backend`

3. Configure o arquivo application.properties com as informações do seu banco de dados MySQL:
`spring.datasource.url=jdbc:mysql://localhost:3306/seu_banco_de_dados
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update`

4. Execute o projeto Spring Boot:
`mvn spring-boot:run`

### Frontend
1. Navegue até o diretório do projeto frontend:
`cd ../frontend`

2. Instale as dependências do projeto:
`npm install`

3. Inicie o servidor de desenvolvimento do React:
`npm start`

### Acessando a Aplicação
- O frontend estará disponível em http://localhost:3000.
- O backend estará disponível em http://localhost:8080.
- 
## Contribuição
Sinta-se à vontade para contribuir com este projeto através de pull requests. Toda ajuda é bem-vinda!

# English
# **Fullstack User CRUD**
This project is a simple CRUD (Create, Read, Update, Delete) system for users, developed as a practical exercise in integrating Frontend and Backend technologies. The application was built using Java and Spring Boot for the Backend, MySQL for the database, and React.js for the Frontend.

## Technologies Used
- Backend:
  - Java
  - Spring Boot
  - JPA/Hibernate
  - MySQL
  - REST API

- Frontend:
  - React.js
  - Axios (for HTTP requests)
  - Bootstrap (for styling)

## Features

- Add User: Allows the creation of a new user with name, username and email.
- List Users: Displays a list of all registered users.
- Update User: Allows editing the information of an existing user.
- Delete User: Allows the removal of a user from the system.

## How to Run the Project
### Prerequisites
- Java 11+
- Maven
- Node.js
- MySQL

### Backend
1. Clone the repository:
`git clone https://github.com/your-username/your-repository.git`

2.Navigate to the backend project directory:
`cd your-repository/backend`

3. Configure the application.properties file with your MySQL database information:
`spring.datasource.url=jdbc:mysql://localhost:3306/your_database
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update`

4. Run the Spring Boot project:
`mvn spring-boot:run`

### Frontend
1. Navigate to the frontend project directory
`cd ../frontend`

2. Install the project dependencies:
`npm install`

3. Start the React development server:
`npm start`

### Accessing the Application
- The frontend will be available at http://localhost:3000.
- The backend will be available at http://localhost:8080.

## Contribution
Feel free to contribute to this project via pull requests. Any help is welcome!
