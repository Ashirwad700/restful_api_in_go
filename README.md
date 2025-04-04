﻿# restful_api_in_go


  RESTful API in Go using Gin 

  About the Project 
This is a simple RESTful API built using the **Gin** web framework in Go. The goal of this project was to learn the fundamentals of building web services in Go, including handling HTTP requests, routing, and middleware integration.  

  Why I Built This 
I wanted to:  
- Get hands-on experience with **Go** and **Gin** for backend development.  
- Understand how to structure a REST API in Go.  
- Learn how to handle different HTTP methods (GET, POST, PUT, DELETE).  
- Experiment with routing, request handling, and JSON responses in Go.  

How to Run  
Prerequisites
Make sure you have **Go** installed on your system. If not, install it from [Go’s official site](https://go.dev/dl/).  

  Steps to Run the API 
1. Clone the repository:  
   ```sh
   git clone https://github.com/Ashirwad700/restful_api_in_go.git
   cd restful_api_in_go
   ```
2. Install dependencies:  
   ```sh
   go mod tidy
   ```
3. Run the server:  
   ```sh
   go run main.go
   ```
4. The API will start at **http://localhost:8080**  

  API Endpoints 
| Method | Endpoint      | Description           |
|--------|-------------|-----------------------|
| GET    | `/ping`     | Returns `"pong"`      |
| POST   | `/data`     | Accepts JSON input    |
| GET    | `/items`    | Fetches all items     |

  Next Steps
- Connect to a database for persistent storage  
- Add authentication and middleware  
- Deploy the API online  

