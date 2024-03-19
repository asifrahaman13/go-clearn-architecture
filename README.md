# About the application


This is a simple Go application that demonstrates a basic project structure and Docker setup.

## Project Structure

The project follows a typical Go project structure:

```bash
.
├── config
│   └── config.go
├── pkg
│   └── pkg.go
├── src
│   ├── cmd
│   │   └── main.go
│   ├── internal
│   │   ├── application
│   │   │   └── user_service.go
│   │   ├── constants
│   │   │   └── constants.go
│   │   ├── domain
│   │   │   └── user.go
│   │   ├── helper
│   │   │   └── helper.go
│   │   ├── infrastructure
│   │   │   └── user_repository.go
│   │   ├── interfaces
│   │   │   ├── route
│   │   │   └── routes.go
│   │   ├── middleware
│   │   │   └── middleware.go
│   │   └── pkg
│   └── test
├── Dockerfile
├── README.md
└── go.mod
```

