# thrust-getting-started

A simple Thrust app, which can easily be deployed to Heroku.

This application support the [Getting Started with Thrust on Heroku](https://github.com/cneryjr).

## Running Locally

Make sure you have Java installed.  Also, install the [Heroku Toolbelt](https://toolbelt.heroku.com/).

```sh
$ git clone https://github.com/cneryjr/thrust-heroku-template.git
$ cd thrust-heroku-template
$ heroku local web
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

If you're going to use a database, ensure you have a local `.env` file that reads something like this:

```
DATABASE_URL=postgres://localhost:5432/gradle_database_name
```

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku master
$ heroku open
```

## Documentation

For more information about using Java on Heroku, see these Dev Center articles:

- [Java on Heroku](https://devcenter.heroku.com/categories/java)