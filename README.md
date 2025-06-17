#  📋  Gerenciador de Tarefas - Spring Boot

Aplicação web para gerenciamento de tarefas utilizando Spring Boot no modelo MVC.

## 🎯 Tecnologias

- Java 17+
- Spring Boot
- Spring Web
- Spring Data JPA
- Spring Data MongoDB
- H2 Database
- MariaDB
- MongoDB
- Lombok
- Validation

##  Funcionalidades

- Listar tarefas
- Criar nova tarefa
- Atualizar tarefa existente
- Deletar tarefa

## Endpoints

- `GET /tarefas` - Lista todas as tarefas
- `POST /tarefas` - Cria uma nova tarefa
- `PUT /tarefas/{id}` - Atualiza uma tarefa
- `DELETE /tarefas/{id}` - Remove uma tarefa

## Banco de Dados

- Configuração padrão: H2
- Opcional: MariaDB e MongoDB (com configuração no `application.properties`)

## Como rodar

1. Clone o projeto
2. Importe no VS Code com suporte a Java e Spring Boot
3. Execute com:

```bash
./mvnw spring-boot:run
