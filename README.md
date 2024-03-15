# Go MongoDB REST API

This is a simple RESTful API built with Go and MongoDB. It provides basic CRUD (Create, Read, Update, Delete) operations for managing users.

## Features

- **Get User**: Retrieve a user by their ID.
- **Create User**: Create a new user with a name, gender, and age.
- **Delete User**: Delete a user by their ID.

## Getting Started

### Prerequisites

- Go (version 1.16 or later)
- MongoDB (version 4.0 or later)

### Installation

1. Clone the repository: `git clone https://github.com/your-username/go-mongodb-rest-api.git`

2. Navigate to the project directory: `cd go-mongodb-rest-api`

3. Start the MongoDB server (if not already running).

4. Run the Go application: `go run main.go`

The server will start running on `http://localhost:9000`.

### Usage

- **Get User**: `GET /user/:id`
- **Create User**: `POST /user` with a JSON payload `{ "name": "John Doe", "gender": "male", "age": 30 }`
- **Delete User**: `DELETE /user/:id`

You can use tools like `curl`, Postman, or a web browser to interact with the API endpoints.

## Dependencies

- [julienschmidt/httprouter](https://github.com/julienschmidt/httprouter) - A lightweight and fast HTTP router for Go.
- [gopkg.in/mgo.v2](https://labix.org/mgo) - A MongoDB driver for the Go language.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.
