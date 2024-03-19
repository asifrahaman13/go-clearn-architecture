# About the application


This is a simple Go application that demonstrates a basic project structure and Docker setup.

## Project Structure

The project follows a typical Go project structure:

```bash
.
├── src
│   ├── cmd
│   │   └── main.go
│   ├── internal
│   │   ├── application
│   │   │   └── user_service.go
│   │   ├── domain
│   │   │   └── user.go
│   │   ├── infrastructure
│   │   │   └── user_repository.go
│   │   ├── interfaces
│   │   │   └── user_handler.go
│   │   └── pkg
│   └── test
├── Dockerfile
├── README.md
└── go.mod
```

