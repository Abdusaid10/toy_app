# toy_app

This is basic application from [railstutorial](https://www.railstutorial.org/book/toy_app), Here we develop a toy demo application to show off some of the power of Rails. The purpose is to get a high-level overview of Ruby on Rails programming (and web development in general) by rapidly generating an application using scaffold generators, which create a large amount of functionality automatically.

## Prerequisite

- Ruby 2.6.3
- Rails 5.2.3

## Getting started


```
git clone https://github.com/Abdusaid10/toy_app.git
cd toy_app
```

To get started with the app, clone the repo and then install the needed gems:

```
bundle install --without production
```

Next, migrate the database:

```
rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
rails server
```

## Author

- [@Abdusaid10](https://github.com/Abdusaid10)
- [@imhta](https://github.com/imhta)
