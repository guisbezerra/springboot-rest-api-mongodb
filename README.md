# REST API - Spring Boot + MongoDB

API REST desenvolvida em Java com Spring Boot e Spring Data MongoDB, utilizando MongoDB para persistência de dados.

O projeto foi desenvolvido com foco na prática de desenvolvimento de APIs REST, persistência de dados NoSQL, organização em camadas e implementação de operações sobre documentos MongoDB.

## 🚀 Tecnologias

- Java 17
- Spring Boot 3.5.6
- Spring Web
- Spring Data MongoDB
- MongoDB
- Maven

## 📚 Conceitos praticados

- Desenvolvimento de APIs REST
- Persistência de dados com MongoDB
- Modelagem de documentos NoSQL
- Operações CRUD
- Consultas com múltiplos critérios
- Organização em camadas
- Data Transfer Objects (DTOs)
- Separação de responsabilidades
- Acesso a dados utilizando Spring Data MongoDB

## 🏗️ Estrutura do projeto

O projeto utiliza uma organização em camadas, separando as principais responsabilidades da aplicação:

- **Config** — configurações da aplicação
- **Domain** — entidades e modelos do domínio
- **DTO** — objetos utilizados para transferência de dados
- **Repository** — acesso e persistência dos dados utilizando Spring Data MongoDB
- **Services** — implementação das regras e lógica da aplicação
- **Resources** — arquivos de configuração e recursos da aplicação

## 🗄️ Banco de dados

O projeto utiliza o **MongoDB** para persistência dos dados.

Configuração utilizada:

- Banco de dados: `oficina_mongo`
- Host: `localhost`
- Porta: `27017`

A aplicação utiliza a seguinte conexão:

```text
mongodb://localhost:27017/oficina_mongo
```

## ⚙️ Como executar

### Pré-requisitos

- Java 17
- Maven
- MongoDB

### 1. Clone o repositório

```bash
git clone https://github.com/guisbezerra/springboot-rest-api-mongodb.git
```

### 2. Acesse o diretório do projeto

```bash
cd springboot-rest-api-mongodb
```

### 3. Inicie o MongoDB

Certifique-se de que o MongoDB esteja em execução localmente na porta padrão `27017`.

### 4. Execute a aplicação

Utilizando o Maven Wrapper:

```bash
./mvnw spring-boot:run
```

No Windows:

```bash
mvnw.cmd spring-boot:run
```

A aplicação será iniciada utilizando a configuração definida no projeto.

## 🎯 Objetivo

Projeto desenvolvido para consolidar conhecimentos em desenvolvimento backend com Java e Spring Boot, explorando a construção de APIs REST, persistência de dados NoSQL com MongoDB e organização de aplicações utilizando uma arquitetura em camadas.
