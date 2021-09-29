<h1 align="center">Payroll</h1>

<p align="center">
  
  <img alt="Modelo Conceitual" src="https://github.com/VivianneMiranda/Payroll/blob/main/Modelo_Conceitual.jpeg" width="350">
</p> 

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Java 11](https://www.oracle.com/br/java/technologies/javase/javase-jdk11-downloads.html)
- [PostgreSQL](https://www.postgresql.org/)
- [Spring Boot](https://spring.io/projects/spring-boot)

## 💻 Projeto

Valoriza é uma plataforma para promover o reconhecimento entre companheiros de equipe.

### Regras
- Cadastro de usuário

    - Não é permitido cadastrar mais de um usuário com o mesmo e-mail

    - Não é permitido cadastrar usuário sem e-mail

- Cadastro de TAG

    - Não é permitido cadastrar tag sem nome

    - Não é permitido cadastrar mais de uma tag com o mesmo nome

    - Não é permitido o cadastro por usuários que não sejam administradores

- Cadastro de elogios

    - Não é permitido um usuário cadastrar um elogio para si

    - Não é permitido cadastrar elogios para usuários inválidos

    - O usuário precisa estar autenticado na aplicação




## 🚀 Como executar

- Clone o repositório
- Rode `yarn` para baixar as dependências
- Rode `yarn typeorm migration:run` para criar as tabelas do banco de dados.
- Rode o `yarn dev` para iniciar a aplicação.

Por fim, a aplicação estará disponível em `http://localhost:3000`


---
Feito com 💜 &nbsp;by Vivianne Miranda👋🏻 &nbsp;
