# 📚 Biblioteca Online
Uma aplicação web para gerenciamento de livros, desenvolvida como parte do Projeto Integrador II do curso de Análise e Desenvolvimento de Sistemas pelo Senac-RS.

## 🚧 Status do Projeto
Projeto iniciado como uma proposta de sistema web, mas que não teve seu desenvolvimento concluído. Posteriormente, a ideia foi retomada em uma aplicação desktop, utilizando Java Swing, no projeto Biblioteca Digital.

## 🛠️ Tecnologias Utilizadas
- Frontend: HTML, CSS, JavaScript
- Backend: Java, Spring Boot
- Banco de Dados: MySQL com Spring Data JPA

## 🎯 Objetivo do Software
Desenvolver um sistema web que facilite o gerenciamento de uma biblioteca, permitindo controlar o acervo, os usuários e as operações de empréstimo e devolução de livros.

## 📝 Funcionalidades Implementadas
- Listagem dos livros cadastrados;
- cadastro de livros com título, autor e ano de publicação;
- busca de livros por título ou autor;
- API REST para operações relacionadas aos livros.

## ⚙️ Configuração
- Aplicação executada na porta 8081.
- O programa tenta inicializar o banco de dados com o usuário registrado nas variáveis do sistema.
- Caso ele não exista, é necessário ajustar o usuário e senha em src/main/resources/application.properties.
- **Exemplo:**
    ```properties
    spring.datasource.username=root
    spring.datasource.password=0000
    ```
- O banco de dados é criado automaticamente caso não exista.
- O projeto acompanha o arquivo "data.sql", que cria e popula a tabela livros ao iniciar (caso não exista e não esteja populada).

## 👨‍💻 Autor
- Guilherme de Carvalho Gois
