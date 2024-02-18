# Movie CRUD API in Golang

This is a simple project of a CRUD (Create, Read, Update, Delete) API to manage movie information. The API was developed in Golang and uses the Gorilla Mux package for HTTP routing.

<p align="center">
  <img src="go-movies.png" alt="gopher movies project banner">
</p>

## Prerequisites

Make sure you have Go installed on your machine. You can download and install it from the [official website](https://golang.org/).

## Installation

To install the project, clone this repository to your local machine:

```bash
git clone https://github.com/Wtheodoro/go-cinema-crud
```

## Usage

Navigate to the project directory:

- cd go-cinema-crud

Run the project using the go run command:

- go run main.go

## Endpoints da API

- `GET /movies`: Retorna uma lista de todos os filmes.
- `GET /movies/{id}`: Retorna informações sobre um filme específico com o ID fornecido.
- `POST /movies`: Adiciona um novo filme à lista.
- `PUT /movies/{id}`: Atualiza as informações de um filme com o ID fornecido.
- `DELETE /movies/{id}`: Remove um filme com o ID fornecido da lista.

## Example Request

### Add a New Movie

```bash
curl -X POST -H "Content-Type: application/json" -d '{"isbn":"123456","title":"New Movie","director":{"firstname":"Director","lastname":"Lastname"}}' http://localhost:8000/movies
```

## Contribution

Feel free to contribute improvements to this project! Just open an issue or send a pull request.
