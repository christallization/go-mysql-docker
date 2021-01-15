# go-mysql-docker
This a simple Go and Mysql Stack that is initialized in a Docker Container

# To Build From Within Docker
- docker-compose up --build
- docker exec -it golang_app bash
- go run main.go

# Local From Machine
- docker exec -it golang_app bash -c "go run main.go"