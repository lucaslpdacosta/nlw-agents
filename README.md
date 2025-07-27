# NLW Agents

Este projeto foi desenvolvido durante a 20ª NLW da Rocketseat. Este é um projeto para o gerenciamento de salas, utilizando tecnologias como **Node.js**, **TypeScript** e **Drizzle ORM**.

## Tecnologias e Ferramentas

- **Node.js** – Plataforma para execução de código JavaScript no backend
- **TypeScript** – Superset do JavaScript com tipagem estática
- **Drizzle ORM** – Mapeamento objeto-relacional simples e eficiente
- **SQLite** – Banco de dados leve, integrado por meio do Drizzle
- **Zod** – Biblioteca para validação de esquemas de dados
- **Fastify** – Framework HTTP de alto desempenho
- **dotenv** – Carregamento de variáveis de ambiente a partir de um arquivo `.env`

## Banco de dados

O projeto utiliza **Drizzle ORM** para gerenciar a persistência de dados.

![Image](https://github.com/user-attachments/assets/cab00cfb-1678-41e9-8dbf-5f7f273a2d6b)

## Como Rodar o Projeto

### 1. Clone o repositório

```sh
git clone https://github.com/lucaslpdacosta/nlw-agents.git
```

### 2. Crie um arquivo `.env` na raiz do projeto com as seguintes chaves (substitua os valores reais):

```
DATABASE_URL=******
PORT=******
```

### 3. Instale as dependências:

```sh
npm install
```

### 4. Execute as migrations:

```sh
npx drizzle-kit migrate
```

### 5. Inicie o servidor com o script:

```sh
npm run dev
```

### 6. Acesse a URL:

```sh
http://localhost:3000/
```
