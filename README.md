Projeto: Spring Boot JPA + H2 — Análise Estática e Refatoração
Aluna

Beatriz Silveira Caires — Curso de Análise e Desenvolvimento de Sistemas

Descrição

Este projeto foi desenvolvido como parte da Atividade Prática de Análise Estática e Refatoração de Código.
A aplicação foi construída em Spring Boot, utilizando Spring Data JPA e banco de dados H2.
O sistema realiza operações CRUD de tutoriais, permitindo cadastrar, listar, atualizar e excluir registros por meio de endpoints REST.

Análise Estática

Durante a análise, foram observados alguns pontos de melhoria, como:

Complexidade e legibilidade do código

Ausência de validações e logs

Tratamento genérico de exceções

Refatorações

Com base nos problemas identificados, foram feitas as seguintes melhorias:

Adição de validações com @NotBlank

Implementação de um tratamento global de exceções usando @ControllerAdvice

Inclusão de logs e comentários para melhor rastreabilidade

Organização das classes e pacotes

Tecnologias Utilizadas

Java 17

Spring Boot

Spring Data JPA

H2 Database

Maven

SonarQube

Resultados

Após as refatorações, o código ficou mais limpo, seguro e bem estruturado.
As validações e logs trouxeram mais confiabilidade ao sistema, e o padrão de organização facilitou a manutenção do projeto.


