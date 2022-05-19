### Como iniciar

-- após clonar o repositorio, inicie com esse comando --> yarn add json-server json-server-auth

### Inicie o servidor

-- node server.js

### para testar no Insomnia

-- https://localhost:3001/login ou /register
-- localhost:3001/login
-- https://localhost:3001/login ou /register
-- localhost:3001/login

### Cadastro

POST /register <br/>
POST /signup <br/>
POST /users

Qualquer um desses 3 endpoints irá cadastrar o usuário na lista de "Users", sendo que os campos obrigatórios são os de email e password.
Você pode ficar a vontade para adicionar qualquer outra propriedade no corpo do cadastro dos usuários.

### Login

POST /login <br/>
POST /signin

Qualquer um desses 2 endpoints pode ser usado para realizar login com um dos usuários cadastrados na lista de "Users"
