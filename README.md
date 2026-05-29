🚀 Workshop JPA: Sistema de Gerenciamento de Pedidos
Este projeto é uma API RESTful desenvolvida em Java com Spring Boot, focada no aprendizado de mapeamento objeto-relacional (ORM) com JPA/Hibernate. O objetivo é gerenciar usuários, pedidos, produtos e categorias, aplicando boas práticas de arquitetura em camadas e integração com banco de dados PostgreSQL.

🛠️ Tecnologias Utilizadas
Java 25

Spring Boot 4.x (Spring Data JPA, Spring Web)

PostgreSQL (Banco de dados de desenvolvimento)

Maven (Gerenciamento de dependências)

Hibernate (Implementação JPA)

🏗️ Arquitetura do Projeto
O projeto segue o padrão de camadas para garantir organização e manutenibilidade:

Resource (Controller): Gerencia as requisições HTTP (API REST).

Service: Contém a lógica de negócio e trata exceções.

Repository: Camada de acesso a dados (JPA).

Entities: Definição dos modelos de dados (Mapeamento JPA).

📚 Endpoints Principais
A API responde nos seguintes caminhos (base http://localhost:8080):
Método,Endpoint,Descrição
GET,/users,Lista todos os usuários
GET,/users/{id},Busca usuário específico
POST,/users,Cria um novo usuário
GET,/products,Lista todos os produtos

🤝 Contribuições
Sinta-se à vontade para abrir issues ou enviar pull requests. Este projeto foi desenvolvido para fins acadêmicos como parte de um workshop de JPA.
