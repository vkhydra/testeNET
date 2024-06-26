# Teste para candidatos à vaga de Desenvolvedor .NET

Olá caro desenvolvedor, nesse teste analisaremos seu conhecimento geral e inclusive velocidade de desenvolvimento. Abaixo explicaremos tudo o que será necessário.

## Instruções

O desafio consiste em implementar uma aplicação web utilizando .NET, um banco de dados relacional (SQL Server, Mysql, PostgreSQL ou SQLite), que terá como finalidade a inscrição de candidatos a uma oportunidade de emprego.

Sua aplicação deve possuir:

- CRUD de vagas:
  - Criar, editar, excluir e listar vagas.
  - A vaga pode ser CLT, Pessoa Jurídica ou Freelancer.
- CRUD de candidatos:
  - Criar, editar, excluir e listar candidatos.
- Um cadidato pode se inscrever em uma ou mais vagas.
- Deve ser ser possível "pausar" a vaga, evitando a inscrição de candidatos.
- Cada CRUD:
  - Deve ser filtrável e ordenável por qualquer campo, e possuir paginação de 20 itens.
  - Deve possuir formulários para criação e atualização de seus itens.
  - Deve permitir a deleção de qualquer item de sua lista.
  - Implementar validações de campos obrigatórios e tipos de dados.

## Banco de dados

- Você pode criar a modelagem e implementar as validações necessárias da camada da forma que julgar melhor.

## Tecnologias a serem utilizadas

Devem ser utilizadas as seguintes tecnologias:

- HTML
- CSS
- Javascript
- .NET (Framework Opcional: ASP.NET Core)
- Docker (construção do ambiente de desenvolvimento)
- SQL Server, Mysql, PostgreSQL ou SQLite

## Entrega

- Para iniciar o teste, faça um fork deste repositório; **Se você apenas clonar o repositório não vai conseguir fazer push.**
- Crie uma branch com o seu nome completo;
- Altere o arquivo teste-net.md com as informações necessárias para executar o seu teste (comandos, instalações, etc);
- Depois de finalizado, envie-nos o pull request;

## Bônus

- API Rest JSON para todos os CRUDS listados acima.
- Permitir deleção em massa de itens nos CRUDs.
- Permitir que o usuário mude o número de itens por página.
- Implementar autenticação de usuário na aplicação.

## O que iremos analisar

- Organização do código;
- Conhecimento de padrões (SOLID, design patterns);
- Separação de módulos e componentes;
- Legibilidade;
- Tratamento de erros;

### Boa sorte!