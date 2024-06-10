# Go Playground

This project serves as a playground for exploring the [Go](https://go.dev/)
programming language.

## Prerequisites

Ensure the following requirements are met prior to usage:

- Go [installed](https://go.dev/dl/)

## Build Code

```sh
go build -o ./bin/playground ./src/playground.go
```

The build artifacts are placed in the `bin` directory. Run the executable using:

```sh
./bin/playground
```

## Run Code

Code can be run without building using the following command:

```sh
go run ./src/playground.go
```

## Run Tests

```sh
go test ./src
```
