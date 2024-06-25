# Projeto: Formulário Web CRUD com Spring Boot
Este projeto é uma aplicação web de CRUD (Create, Read, Update, Delete) desenvolvida utilizando o framework Spring Boot. O objetivo principal é demonstrar a criação de um formulário web com operações básicas de gerenciamento de dados. A aplicação segue a arquitetura MVC (Model-View-Controller) e utiliza diversas tecnologias e ferramentas para sua construção.


## Funcionalidades
Criação de registros: Permite a adição de novos registros ao banco de dados.
Leitura de registros: Exibe a lista de registros armazenados no banco de dados.
Atualização de registros: Permite a edição de registros existentes.
Exclusão de registros: Possibilita a remoção de registros do banco de dados.

## Tecnologias Utilizadas
* **Java:** Linguagem de programação principal.
* **Spring Boot:** Framework utilizado para facilitar o desenvolvimento da aplicação.
* **Maven:** Ferramenta de automação de build e gerenciamento de dependências.
* **H2 Database:** Banco de dados em memória utilizado para armazenar os dados da aplicação.
* **JPA (Java Persistence API):** Utilizado para a persistência de dados.
* **Spring DevTools:** Ferramenta para acelerar o desenvolvimento e a depuração.
* **Spring Starter Validation:** Utilizado para validação dos dados do formulário.
* **HTML:** Linguagem de marcação utilizada para criar as páginas da web.
* **Bootstrap:** Framework CSS utilizado para estilizar as páginas do formulário.

## Estrutura do Projeto
A aplicação segue a arquitetura MVC, dividida nas seguintes camadas:

* **Model:** Representa as entidades e a lógica de negócios da aplicação. Utiliza JPA para mapeamento objeto-relacional.
* **View:** Camada responsável pela interface com o usuário. Utiliza HTML e Bootstrap para criar um design simples e responsivo.
* **Controller:** Camada que gerencia as requisições HTTP e interage com a camada de Model para processar os dados e retornar as respostas apropriadas.

## Considerações Finais
Este projeto é uma implementação básica de um formulário web com operações CRUD utilizando Spring Boot e outras tecnologias. Ele pode ser expandido e adaptado conforme as necessidades específicas de cada aplicação. Contributions e sugestões são bem-vindas!
