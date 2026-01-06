# Node.js (REST API) + Angular + MySQL

This is a boilerplate project. The project contains Node.js REST API and frontend developed by Angular.

- API
  - Node.js, Express, JWT, Promise MySQL, Node Mailer Nodemon
- Frontend - Angular
  - Material ui, Toastr


```bash
# Front
cd frontend-angular
npm start
```

```bash
# Api
cd api
npm run build
npm run dev
```
Then you can access services with below URL.

| Service            | Endpoint                                                         |
| ------------------ | ---------------------------------------------------------------- |
| API                | [http://localhost:3000](http://localhost:3000)                   |
| Frontend           | [http://localhost:4200](http://localhost:4200)|
| MySQL              | localhost:3307                                                   |

There are two user in the database initially. You can use them to login Frontend.

| Username | Email              | Password |
| -------- | ------------------ | -------- |
| admin    | admin@.local | 123456   |
| user     | user@.local  | 123456   |


### MySQL

In the folder `mysql/sql`, there is a SQL file called `inital.sql`, which will become initial database table/rows. MySQL
port is mapped to 3307.

## Features

- Frontend - Angular

  - User registration
  - Confirm user email address
  - Reset user password
  - User login/logout

## Todo
- [x] Docker
- [ ] CI/CD
- [ ] Unit tests
- [ ] E2E tests
