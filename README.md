# dslist-spring

## Descrição
Este projeto é uma API para listar e gerenciar jogos em listas, de acordo com a categoria de cada um. 
Dessa forma, é possível buscar todos os jogos ou somente um e também filtrar por listas e buscar um único jogo pertencente à essa lista.

## Tecnologias utilizadas:
- Spring Boot 3
- Maven
- Spring Data JPA

## Conceitos abordados:
- Padrão Rest para API web
- Database seeding
- Entidades e ORM
- Padrão de camadas
- Controller, service, repository
- Padrão DTO
- Relacionamentos N-N
- Consultas SQL no Spring Data JPA
- Classe de associação, embedded id

## Endpoints:
Este projeto oferece alguns endpoints. Você pode testá-los usando um cliente REST, como, por exemplo, o Postman. Aqui estão alguns exemplos de endpoints disponíveis:
- `GET /games`: retorna todos os jogos do banco de dados.
- `GET /games/{id}`: retorna um jogo específico com o ID fornecido.
- `GET /lists`: retorna todos as listas de cada categoria de jogos existentes
- `GET /lists/{id}/games`: retorna a lista com ID especificado e todos os jogos pertencentes à ela.
- `POST /lists/{id}/replacement`: permite mover o jogo e reposicionar em qualquer posição da lista.
