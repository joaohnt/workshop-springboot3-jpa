# Workshop: API de Controle de Pedidos e Usuários com Spring Boot e JPA
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/joaohnt/workshop-springboot3-jpa/blob/main/LICENSE) 

# Sobre o projeto

Este projeto é uma API RESTful desenvolvida com Spring Boot para gerenciar dados de usuários, oferecendo operações CRUD (Criar, Ler, Atualizar, Excluir). Ele utiliza JPA para persistência de dados e um banco de dados em memória H2 para desenvolvimento. Também implementa tratamento de exceções personalizadas para retornar mensagens claras de erro quando recursos não são encontrados ou há violação de restrições do banco de dados.

Foi desenvolvido como parte do curso de Java da DevSuperior na Udemy e pode ser testado facilmente com o Postman ou outras ferramentas de teste de API..

## Modelo conceitual
![Modelo Conceitual](https://github.com/user-attachments/assets/cae98a92-7003-47f3-abf4-6758a78d9336)

# Tecnologias utilizadas
- Java
- Spring Boot
- JPA / Hibernate
- Maven
- Postman

# Como executar o projeto

## Back end
Pré-requisitos: JDK 17 ou superior e Maven

```bash
#Clone o repositório:
git clone https://github.com/joaohnt/workshop-springboot3-jpa.git

#Instale as dependências: No diretório raiz do projeto, execute o seguinte comando para baixar as dependências:
mvn clean install

#Execute a aplicação: Inicie o servidor Spring Boot usando o Maven:
mvn spring-boot:run
```
Acesse a aplicação: O servidor estará rodando em http://localhost:8080. Você pode usar ferramentas como Postman para testar os endpoints.
Para testar todas as funções da API, você pode fazer requisições CRUD para a entidade /users

Para listar usuários: GET /users

Para buscar um usuário específico: GET /users/{id}

Para criar um novo usuário: POST /users

Para atualizar um usuário: PUT /users/{id}

Para excluir um usuário: DELETE /users/{id}

Você também pode listar todos os itens ou buscar por ID nas entidades: produtos (/products), pedidos (/orders) e categorias (/categories).


# João Pedro Carvalho Garcia

https://www.linkedin.com/in/joaohnt
