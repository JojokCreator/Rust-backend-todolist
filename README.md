# Rust Backend and link to postgres db

A simple backend written in Rust that connects to a postgres database. It uses the Rocket.rs framework and Diesel to communicate with the database.

### Features

- **Add a new Todo** - Adds a new Todo
- **Delete Todo by Id** -  Deletes the Todo by it's ID
- **Update the Todo Status** - Changes the Id status from false to true(ie the task is done)

## API Reference

#### Get all items

```bash
  GET /todos/
```

#### Update item status

```bash
  PUT /todos/${id}
```

#### Delete item by ID

```bash
  Delete /todos/delete/${id}
```

#### Create

```bash
  POST /todos/
```

```bash
todo (id) {
        id -> Int4,
        title -> Varchar,
        checked -> Bool,
    }
 ```
 
### Links

- Live Site URL: [Deployed on Heroku](https://floating-atoll-63470.herokuapp.com/hello/coder)

### Built using

- [Rust](https://www.rust-lang.org/)
- [Rocket](https://rocket.rs/)
- [Diesel](https://diesel.rs/)
