# Aviator

Este projeto utiliza o padrão Mediator para organizar a comunicação entre diferentes partes da aplicação. Abaixo estão os comandos utilizados para configurar a estrutura inicial do projeto:

### Estrutura do Projeto

- **Aviator.Domain**: Biblioteca de classes para as entidades e regras de negócio.
  ```bash
  dotnet new classlib -o Aviator.Domain
  ```
- **Aviator.Aplication**: Biblioteca de classes para a lógica de aplicação.
  ```bash
  dotnet new classlib -o Aviator.Aplication
  ```
- **Aviator.Infrastructure**: Biblioteca de classes para a infraestrutura e acesso a dados.
  ```bash
  dotnet new classlib -o Aviator.Infrastructure
  ```
- **Aviator.Api**: Projeto web para expor a API da aplicação.
  ```bash
  dotnet new web -o Aviator.Api
  ```