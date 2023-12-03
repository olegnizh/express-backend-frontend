# app1
## RESTful API with Node.js, Express, and Postgres
This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

## Database postgresql

``` postgresql: postgres, admin

```sql
CREATE TABLE users (
  ID SERIAL PRIMARY KEY,
  name VARCHAR(30),
  email VARCHAR(30)
);

INSERT INTO users (name, email)
  VALUES ('Empty', 'Empty@example.com'), ('Кирилл', 'kirill@example.com');
```
## Installation

```bash

git clone https://github.com/olegnizh/express-backend-frontend.git
cd express-backend-frontend
npm install
node index.js
```
## Commands

- GET: `curl http://localhost:3000/users`
- POST: `curl --data "name=Alex&email=Alex@example.com" http://localhost:3000/users`
- PUT: `curl -X PUT -d "name=Empty" -d "email=Alone@example.com" http://localhost:3000/users/1`
- DELETE: `curl -X "DELETE" http://localhost:3000/users/1`


