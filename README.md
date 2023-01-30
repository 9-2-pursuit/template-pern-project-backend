# PERN Final Project Template

- select `use this template`
- clone this repo

## Getting Started

#### Basic App

- `npm install`
- `touch .env`

make sure you are on the same level as the `package.json`

- `touch .env`

```
PORT=3333
PG_HOST=localhost
PG_PORT=5432
PG_DATABASE=template_test_dev
PG_USER=postgres
PG_PASSWORD=""
```

- `npm run db:init`
- `npm run db:seed`

Test app locally. If it does not work locally, it will not work on Heroku.

Fix bugs.

When you are ready, deploy this app.
