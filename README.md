# AngularCRUD

An employee dashboard built with Angular 17. It does full CRUD (add, list, edit, delete) on employee records: first name, last name, email, mobile and salary.

The data comes from a mock REST API run by [json-server](https://github.com/typicode/json-server) on top of `db.json`.

## Run it

```bash
npm install
npm run api     # mock API on http://localhost:3000/posts
npm start       # app on http://localhost:4200 (in a second terminal)
```

Both must be running. The app calls `http://localhost:3000/posts` for every request, so without `npm run api` it shows no data.

`db.json` holds a few fake sample rows, and json-server writes your changes back to it.

## Other commands

- `npm run build` builds the app into `dist/`.
- `npm test` runs the unit tests (Karma and Jasmine).

## Stack

Angular 17, RxJS, json-server.
