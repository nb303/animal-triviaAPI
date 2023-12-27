# animal-triviaAPI

A simple API for animal trivia facts! Built with Go, Fiber, and PostgreSQL.

## To Use

Have the following installed

- [Docker](https://www.docker.com/get-started)
- [Go](https://golang.org/doc/install)
- [PostgreSQL](https://www.postgresql.org/download/)

1. Clone the repository
   ```bash
    git clone https://github.com/nb303/animal-triviaAPI.git
    ```
2. Go to project directory
   ```bash
    cd animal-triviaAPI
    ```
3. Set up your environment variables in a .env file
  ```env
    DB_USER=your_postgres_user
    DB_PASSWORD=your_postgres_password
    DB_NAME=your_database_name
    ```

4. Build and run the Docker containers
   ```bash
    docker-compose up --build
    ```
5. Access the API at
   [localhost:3001](http://localhost:3001)

  

