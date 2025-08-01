<h1 align="center">API Gateway do projeto bookrate</h1>

![GitHub Org's stars](https://img.shields.io/github/license/Artur-Neves/Gerenciamento-escolar_java)
&nbsp;
![Badge Finalizado](http://img.shields.io/static/v1?label=STATUS&message=finalizado)

Este é o serviço que faz o papel de API Gateway do projeto <a href="https://github.com/Artur-Neves/bookrate" target="_blank">bookrate</a>. Ele centraliza e gerencia todas as requisições externas ao sistema, roteando para os serviços apropriados. O projeto foi desenvolvido em Java, utilizando o Spring Boot com bibliotecas do Spring Cloud.

<br>

# :hammer: Funcionalidades do projeto

- **`API Gateway`**: Gerencia e encaminha as requisições dos clientes para os microsserviços corretos, atuando como ponto de entrada única do sistema.
- **`Load Balancer`**: Distribui as requisições entre múltiplas instâncias dos serviços registrados, garantindo alta disponibilidade e escalabilidade.
- **`Swagger documentation`**: Disponibiliza uma interface interativa para visualização e testes das APIs expostas.

<br>

## ✔️ Técnicas e tecnologias utilizadas

As técnicas e tecnologias utilizadas no projeto foram:

- **`Spring Cloud Gateway`**: Gerencia o roteamento, filtros e redirecionamento de requisições.
- **`Spring Cloud Netflix Eureka Client`**: Descoberta de serviços para registrar e localizar os microsserviços dinamicamente.
- **`Java 17`**: Linguagem principal utilizada no desenvolvimento.
- **`Maven`**: Ferramenta de automação de build e gerenciamento de dependências.
- **`Swagger/OpenAPI`**: Documentação acessível das APIs para facilitar testes e integração.
- **`Docker`**: Utilizado para a containerização e orquestração do microsserviço.

<br>


