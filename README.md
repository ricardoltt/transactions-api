# Projeto de Estudos: API REST com Fastify, Knex e TypeScript

Este é um projeto de estudos que consiste na criação de uma API REST utilizando Fastify, Knex, Zod, TypeScript e outras ferramentas auxiliares. O objetivo é praticar o desenvolvimento de APIs robustas e eficientes, bem como a escrita de testes automatizados para garantir a qualidade do código.

## Tecnologias Utilizadas

- **[Fastify](https://www.fastify.io/)**: Um framework web rápido e de baixa sobrecarga para Node.js.
- **[Knex](http://knexjs.org/)**: Um SQL query builder para Node.js.
- **[TypeScript](https://www.typescriptlang.org/)**: Um superconjunto de JavaScript que adiciona tipagem estática ao idioma.
- **[Zod](https://github.com/colinhacks/zod)**: Um esquema de declaração e validação de TypeScript.
- **[Vitest](https://vitest.dev/)**: Um testador de unidade rápido e leve para projetos TypeScript.
- **[supertest](https://github.com/visionmedia/supertest)**: Um módulo para testar APIs HTTP.

## Funcionalidades

**Requisitos Funcionais (RF)**

- [x] O usuário deve poder criar uma nova transação.
- [x] O usuário deve poder obter um resumo da sua conta.
- [x] O usuário deve poder listar todas as transações que já ocorreram.
- [x] O usuário deve poder visualizar uma transação única.

**Regras de Negócio (RN)**

- [x] A transação pode ser do tipo crédito que somará ao valor total, ou débito que subtrairá do valor total.

## Como Executar o Projeto

### Pré-requisitos

- Node.js
- npm ou yarn

### Instalação

1. Clone o repositório:

```bash
git clone https://github.com/ricardoltt/transactions-api
```

2. Acesse o diretório do projeto:

```bash
cd seu-repositorio
```

3. Instale as dependências:

```bash
npm install
```

### Configuração

1. Configure o banco de dados no arquivo database.ts conforme suas necessidades.

2. Crie os arquivos .env conforme os exemplos do projeto.

3. Execute as migrações do banco de dados:

```bash
npm run knex -- migrate:latest
```

### Execução

1. Para iniciar a aplicação em modo de desenvolvimento:

```bash
npm run dev
```

A API estará disponível em http://localhost:3333.

### Testes
Para executar os testes, utilize o comando:

```bash
npm test
```

<p align="center">
  Feito com ❤️ por <a href="https://github.com/ricardoltt">Ricardo</a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ricardoltt">
    <img src="https://img.shields.io/badge/LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=0A66C2">
  </a>
  <a href="mailto:ricardo.ltemoteo@gmail.com">
    <img src="https://img.shields.io/badge/Email-000?style=for-the-badge&logo=gmail&logoColor=EA4335">
  </a>
  <a href="https://github.com/ricardoltt">
    <img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white">
  </a>
</p>
<div align="center"><img src="https://visitor-badge.glitch.me/badge?page_id=ricardoltt.transactions-api" alt="visitor badge"/></div>

