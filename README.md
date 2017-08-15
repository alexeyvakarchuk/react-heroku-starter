### Installation

Install the dependencies at first.
If you want to run the project in development mode run this:

```sh
$ npm run dev
```

### For production setup

```sh
$ webpack -p --config ./webpack-prod.config.js
$ npm start
```
(or you can just deploy it to Heroku and it'll build this on the server)

### If you want to check linting run this:

```sh
$ npm run lint
```