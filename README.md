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

- Adicionar Usuário: Permite a criação de um novo usuário com nome, email e idade.
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

## Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.
