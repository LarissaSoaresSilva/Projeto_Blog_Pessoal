<p align="center">
  <img src="https://github.com/user-attachments/assets/64d3f6ef-503c-44eb-9f5d-5062fae30c75" alt="Banner do Projeto">
</p>

<h1 align="center">🕹️ Projeto Blog Pessoal </h1>

<p align="center">
  <img src="https://img.shields.io/badge/status-em%20desenvolvimento-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Java-17-blueviolet?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-2.7.5-brightgreen?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Maven-3.8.6-orange?style=for-the-badge&logo=apachemaven&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Insomnia-4000BF?style=for-the-badge&logo=insomnia&logoColor=white" />
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" />
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white" />
</p>

<p align="center">
  <a href="#descrição-do-projeto">Descrição</a> •
  <a href="#tecnologias-utilizadas">Tecnologias</a> •
  <a href="#funcionalidades">Funcionalidades</a> •
  <a href="#estrutura-do-projeto">Estrutura</a> •
  <a href="#como-executar-o-projeto">Como Executar</a> •
  <a href="#melhorias-futuras">Melhorias Futuras</a> 
</p>

##

## 📄 Descrição do Projeto

O **Projeto Blog Pessoal** é uma aplicação **back-end RESTful** desenvolvida com **Java 17 e Spring Boot**, que simula uma plataforma de blog, permitindo a criação e gerenciamento de postagens por usuários autenticados. 

Este projeto foi desenvolvido como parte do bootcamp da **Generation Brasil** com foco em práticas modernas de desenvolvimento web, utilizando arquitetura MVC, persistência com banco de dados relacional e segurança com Spring Security.

A aplicação oferece endpoints para cadastro e autenticação de usuários, além do gerenciamento completo de postagens e temas. A documentação da API é fornecida via **Swagger**, facilitando a navegação pelos recursos da aplicação. A persistência é feita com **PostgreSQL**, e o sistema está implantado no **Render**, permitindo fácil acesso e testes.

O projeto tem como objetivo reforçar os seguintes conceitos:

- Construção de APIs RESTful modernas
- Boas práticas de arquitetura em **Spring Boot**
- Integração com banco de dados relacional via **JPA**
- Testes de API com ferramentas como **Insomnia**
- Documentação interativa com **Swagger**
- Deploy em nuvem utilizando **Render**
- Versionamento com **Git/GitHub**

A próxima etapa será a construção de uma interface front-end para tornar a aplicação **fullstack completa**.

##

## 🛠️ Tecnologias Utilizadas

- Java 17
- Spring Boot
- Spring Data JPA
- Maven
- PostgreSQL (banco de dados)
- Swagger (documentação da API)
- Insomnia (para teste de API)
- Render (deploy da aplicação)

##

## ⚙️ Funcionalidades

- Cadastro e autenticação de usuários
- Login com token básico (Spring Security)
- Criação, leitura, atualização e exclusão de postagens
- Associação de postagens com temas
- Filtros por título, tema e usuário

##

## 📁 Estrutura do Projeto

```
Projeto_Blog_Pessoal/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── generation/
│   │   │           └── blogpessoal/
│   │   │               ├── controller/
│   │   │               ├── model/
│   │   │               ├── repository/
│   │   │               ├── service/
│   │   │               └── BlogPessoalApplication.java
│   │   └── resources/
│   │       └── application.properties
├── pom.xml
└── README.md
```

##

## 🚀 Como Executar o Projeto

#### Pré-requisitos

- Java 17+
- MySQL
- Maven
- IDE (IntelliJ, Eclipse, VS Code)

#### Passos para rodar:

1. **Clone o repositório**
```
git clone https://github.com/LarissaSoaresSilva/Projeto_Blog_Pessoal.git
```

3. **Configure o `application.properties`**
Atualize com suas credenciais MySQL:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/blog_pessoal
spring.datasource.username=root
spring.datasource.password=sua_senha
```

4. **Execute a aplicação**
```
./mvnw spring-boot:run
```

5. **Acesse**
- API: `http://localhost:8080`
- Teste com Insomnia ou Postman

##

## 🚧 Melhorias Futuras

- Implementar uma interface front-end com React.js para interação com o usuário

- Realizar deploy do front-end em plataformas como Vercel ou Netlify

- Integração completa do front-end com a API back-end via Axios

- Implementar controle de acesso por perfis de usuário (admin, autor, visitante)

- Substituir autenticação básica por JWT (JSON Web Token) para maior segurança

- Permitir comentários em postagens

- Adicionar upload de imagens (ex: capa da postagem ou avatar do usuário)

- Tornar o sistema totalmente responsivo (compatível com mobile e tablets)

- Adicionar testes automatizados (JUnit no back-end, Jest/Cypress no front-end)

##

## 🤝 Contribuições

Contribuições são bem-vindas!  
Você pode:

- Criar uma issue com sugestões de melhoria
- Abrir um Pull Request com ajustes ou novas funcionalidades

##

## 👩🏻‍💻 Desenvolvedora

Feito com 💜 por Larissa Soares!
