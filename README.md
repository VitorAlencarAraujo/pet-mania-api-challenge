# Pet Mania API

API REST desenvolvida em Java com Spring Boot para o gerenciamento de animais, como parte de um desafio prático de desenvolvimento Back-end.

O projeto consiste na análise, identificação e correção de problemas previamente inseridos na aplicação, garantindo o funcionamento adequado dos endpoints e a comunicação com o banco de dados.

## Objetivo do Projeto

O desafio teve como objetivo colocar em prática conhecimentos de desenvolvimento Back-end, investigando e corrigindo problemas em uma API existente.

Ao final, a aplicação deveria permitir o cadastro, a consulta e a exclusão de animais, com suas funcionalidades validadas por meio de requisições HTTP no Postman e da integração com uma interface Front-end disponibilizada para a atividade.

## Tecnologias Utilizadas

- **Java 25**
- **Spring Boot 4.1.2**
- **Spring Data JPA**
- **Spring Web MVC**
- **Maven**
- **MySQL**
- **Postman**

## Funcionalidades

A API disponibiliza operações para o gerenciamento de animais:

- Cadastro de novos animais.
- Consulta de todos os animais cadastrados.
- Consulta de um animal específico pelo ID.
- Exclusão de animais cadastrados.

## Como Executar o Projeto

### Pré-requisitos

Antes de executar a aplicação, é necessário ter instalado:

- Java JDK 25 ou superior.
- MySQL.
- Git.

### 1. Clone o repositório

```bash
git clone https://github.com/VitorAlencarAraujo/pet-mania-api-challenge.git
```

### 2. Acesse a pasta do projeto

```bash
cd pet-mania-api-challenge
```

### 3. Configure o banco de dados

Crie um banco de dados MySQL chamado `petmania`.

```sql
CREATE DATABASE petmania;
```

Configure as credenciais de acesso ao banco de dados no arquivo `application.properties`, localizado em `src/main/resources`.

### 4. Execute a aplicação

Após a inicialização, a API estará disponível localmente em:

```text
http://localhost:8080
```

## Testes da API

Os endpoints foram testados utilizando o Postman, validando as operações de consulta, cadastro e exclusão de animais, assim como as respostas retornadas pela aplicação.

### GET — Consulta de animais

Consulta dos animais cadastrados e busca de um animal específico pelo seu ID.

<img width="886" height="458" alt="image" src="https://github.com/user-attachments/assets/b80b9857-32e4-4e20-bb42-73148ff57e3e" />

### POST — Cadastro de animais

Teste de cadastro de um novo animal por meio de uma requisição POST.

<img width="886" height="458" alt="image" src="https://github.com/user-attachments/assets/780f4168-de7f-4d66-80b3-fb0d5def7f72" />


### DELETE — Exclusão de animais

Teste de exclusão de um animal cadastrado por meio de seu identificador.

<img width="886" height="442" alt="image" src="https://github.com/user-attachments/assets/200e4e04-5af7-49f6-812f-75624fcb6191" />


## 🖥️ Demonstração do Front-end

Além dos testes realizados diretamente no Postman, a aplicação foi integrada ao Front-end Pet Mania, permitindo validar o funcionamento da API por meio de uma interface gráfica.

### Aplicação em funcionamento

<img width="886" height="452" alt="image" src="https://github.com/user-attachments/assets/ff3f5adf-b5cc-4d1b-919d-0d6a6d5fde0b" />


### Cadastro de animais

<img width="886" height="436" alt="image" src="https://github.com/user-attachments/assets/7f2c5de6-0adc-4ba5-85ab-165172e43221" />


### Exclusão de animais

<img width="886" height="456" alt="image" src="https://github.com/user-attachments/assets/934ba75a-dabc-4f3f-bbaa-d1088c7200a2" />


## Aprendizados

O desenvolvimento deste desafio proporcionou a prática de conceitos importantes de desenvolvimento Back-end, incluindo:

- Análise e depuração de código Java.
- Desenvolvimento e funcionamento de APIs REST.
- Utilização do Spring Boot e Spring Data JPA.
- Integração com banco de dados MySQL.
- Implementação e validação de requisições HTTP.
- Testes de endpoints utilizando o Postman.
- Integração entre Back-end e Front-end.

---

**Desenvolvido por [Vitor Alencar](https://github.com/VitorAlencarAraujo)**
