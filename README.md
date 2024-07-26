# CRUD de produtos

Este é um projeto full-stack que utiliza React com Next.js no frontend e Node.js com NestJS no backend.

## Tecnologias Utilizadas

### Frontend

- [React](https://reactjs.org/)
- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Styled-components](https://styled-components.com/) ou [CSS Modules](https://github.com/css-modules/css-modules)
- [Axios](https://axios-http.com/)

### Backend

- [Node.js](https://nodejs.org/)
- [NestJS](https://nestjs.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [TypeORM](https://typeorm.io/) ou [Prisma](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)

## Instalação

### Pré-requisitos

- [Node.js](https://nodejs.org/)

### Backend

1. Navegue até o diretório do backend:
    ```
    cd backend
    ```

2. Instale as dependências:
    ```
    npm install
    ```

3. Configure o arquivo `.env` com as variáveis de ambiente necessárias:
    ```.env
    DATABASE_URL=postgresql://user:password@localhost:5432/projeto1
    PORT=3001
    ```

4. Inicie o servidor de desenvolvimento:
    ```
    npm run start:dev
    ```

### Frontend

1. Navegue até o diretório do frontend:
    ```
    cd frontend
    ```

2. Instale as dependências:
    ```
    npm install
    ```

3. Configure o arquivo `.env` com as variáveis de ambiente necessárias:
    ```.env
    NEXT_PUBLIC_API_URL=http://localhost:3001/api
    PORT=3000
    ```

4. Inicie o servidor de desenvolvimento:
    ```
    npm run dev
    ```
