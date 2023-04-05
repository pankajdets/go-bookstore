BOOKSTORE API using Mysql and with Proper folder structure

Create go.mod  which will store all the packages
go mod init github.com/pankajdets/go-bookstore

Get GORM package which will help to interact with database
go get "github.com/jinzhu/gorm"

Get mysql package
go get "github.com/jinzhu/gorm/dialects/mysql"

install gorilla/mux package : used for route
go get "github.com/gorilla/mux"


To build: go build
To run: go run main.go

