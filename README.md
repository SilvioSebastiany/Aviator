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


### Configuração da Solução

1. Crie a solução principal:
   ```bash
   dotnet new sln

2. Adicione os projetos à solução:
   ```bash 
dotnet sln add Aviator.Api
dotnet sln add Aviator.Domain
dotnet sln add Aviator.Application
dotnet sln add Aviator.Infrastructure

3. Crie o arquivo .gitignore para ignorar arquivos desnecessários no controle de versão:
   ```bash
dotnet new gitignore