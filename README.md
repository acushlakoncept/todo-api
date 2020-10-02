# TODO RESTful JSON API With Rails 6

I built a todo list API where users can manage their to-do lists and todo items.

## Built With

- Ruby v2.6.5
- Ruby on Rails v6.0.3.2
- RSpec-Rails

## Current API Endpoints

Our API will expose the following RESTful endpoints.

| Endpoint                | Functionality                |
|-------------------------|------------------------------|
| POST /signup            | Signup                       |
| POST /auth/login        | Login                        |
| GET /auth/logout        | Logout                       |
| GET /todos              | List all todos               |
| POST /todos             | Create a new todo            |
| GET /todos/:id          | Get a todo                   |
| PUT /todos/:id          | Update a todo                |
| DELETE /todos/:id       | Delete a todo and its items  |
| GET /todos/:id/items    | Get a todo item              |
| PUT /todos/:id/items    | Update a todo item           |
| DELETE /todos/:id/items | Delete a todo item           |



## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

Ruby: 2.6.5
Rails: 6.0.3.2
Postgres: >=9.5

### Setup

~~~bash
$ git clone https://github.com/acushlakoncept/todo-api.git
$ cd todo-api
~~~

Install gems with:

```
bundle install
```

Setup database with:

> make sure you have postgress sql installed and running on your system

```
   rails db:create
   rails db:migrate
```

### Usage

Start server with:

```
    rails server
```

Open `http://localhost:3000/` in your browser.

### Run tests

```
    rpsec 
```

# Authors

👤 **Uduak Essien**

- Github: [@acushlakoncept](https://github.com/acushlakoncept/)
- Twitter: [@acushlakoncept](https://twitter.com/acushlakoncept)
- Linkedin: [acushlakoncept](https://www.linkedin.com/in/acushlakoncept/)


## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Tutorial by [Austin Kabiru](https://www.digitalocean.com/community/tutorials/build-a-restful-json-api-with-rails-5-part-one)