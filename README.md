<h1 align="center">Welcome to Go Simple CRUD API 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1-blue.svg?cacheSeconds=2592000" />
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/fernandesdotts" target="_blank">
    <img alt="Twitter: fernandesdotts" src="https://img.shields.io/twitter/follow/fernandesdotts.svg?style=social" />
  </a>
</p>

> Using go lang to make a simple API service for CRUD movies and learn more about this powerfull language.

## Usage

```sh
go run main.go
```

### Endpoints

- List all movies
    ```http request
    GET http://localhost:8080/movies
    ```

- Get movie by id
    ```http request
    GET http://localhost:8080/movies/{movie_id}
    ```

- Create a new movie
    ```http request
    POST http://localhost:8080/movies
   {
     "isbn": "123456",
     "title": "New Movie",
     "director": {
       "firstname": "Jonh",
       "lastname": "Doe"
     }
   }
    ```

- Update movie by id
    ```http request
    PUT http://localhost:8080/movies/{movie_id}
   {
     "isbn": "654321",
     "title": "Updated Movie",
     "director": {
       "firstname": "Jonh 2",
       "lastname": "Doe 2"
     }
   }
    ```

- Delete movie by id
    ```http request
    DELETE http://localhost:8080/movies/{movie_id}
    ```

## Author

👤 **Eduardo Fernandes**

* Twitter: [@fernandesdotts](https://twitter.com/fernandesdotts)
* Github: [@fernandes-dev](https://github.com/fernandes-dev)
* LinkedIn: [@fernandes-dev](https://linkedin.com/in/fernandes-dev)

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_