# GoDB with Echo - Golang Database Operations

## Description
GoDB with Echo is a simple project demonstrating basic database operations in Golang using the Echo framework. It includes functionalities to perform GET, POST, and PUSH operations on a database using Echo, a high performance, minimalist Go web framework.

## Features
- **GET**: Retrieve data from the database.
- **POST**: Add new data to the database.
- **PUSH**: Update existing data in the database.

## Installation

1. **Clone the repository:**

    ```
    git clone https://github.com/Rawipat40/GoDBSQL.git
    ```

2. **Navigate to the project directory:**

    ```
    cd GoDBSQL
    ```

3. **Install dependencies:**

    ```
    go mod tidy
    ```
## Usage

1. **Start the server:**

    ```
    go run main.go
    ```

2. **Access the endpoints:**

    - GET Operations:
        ```
        GET /data
        ```
    - POST Operations:
        ```
        POST /data
        ```
    - PUT Operations:
        ```
        PUT /data/:id
        ```


## Prerequisites
- Go programming language installed on your machine.
- Basic understanding of RESTful APIs and database operations.

## What I Have Learned

Through this project, I have gained valuable insights into:

- Integrating a database with a Golang web application.
- Implementing CRUD operations using Golang and the Echo framework.
- Handling HTTP requests and responses in a web application context.
- Managing dependencies in a Golang project using modules.
