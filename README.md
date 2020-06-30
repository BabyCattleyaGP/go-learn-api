# Golang API

This repository for personal learning material. 
Creating basic API with Go Language.
With test cases, soon to be dockerized.

## Dev Environment

* Go version go1.14.3 windows/amd64

## Database Configuration

* Can used mysql or postgres (choose one in .env file)
* Create `golearnapi` and `golearnapi_test` database

## Run

* Or Run without build `go run main.go`
* Access in `localhost:8080`

## Test

* Go to tests directory `cd tests`
* Run all test cases `go test -v ./...`
* Run spesific package test:
  * cd to the test directory, example: `cd modeltests`
  * Run  `go test -v --run TestFunctionName`
  * Run all test in package `go test -v`


## To Do

* [ ] Dockerizing the application
* [ ] Deploying on Kubernetes
* [ ] Integrate to Travis
* [ ] Deploy the application on Heroku
* [ ] Consuming the API with Flutter.

## Credit tutorial

[Initial Repository](https://github.com/victorsteven/Go-JWT-Postgres-Mysql-Restful-API) by Victor Steven
