# RESTful Web Server in Go

From [Distributed Computing with Go](https://www.packtpub.com/application-development/distributed-computing-go)

## Basic Web Server

[Related Book Notes][notes/hello]

* [Hello][hello]

## REST Server

[Related Book Notes][notes/server]

Run it with `run go main.go`

* [main.go][server/main]
  * `BooksHandler` pkg
    * [common.go][server/books-hander/common]
    * [actions.go][server/books-hander/actions]
    * [handler.go][server/books-hander/handler]

## Rest Client

[Related Book Notes][notes/client]

With the above REST server running, run it with `go run book-client.go`

* [book-client.go][book-client]

## `cURL` Client

[Related Book Notes][notes/curl]

[hello]: hello_server.go
[server/main]: book-server/main.go
[server/books-hander/common]: book-server/books-handler/common.go
[server/books-hander/actions]: book-server/books-handler/actions.go
[server/books-hander/handler]: book-server/books-handler/handler.go
[book-client]: book-client.go
[notes/hello]: https://github.com/trueheart78/book-notes/blob/master/distributed-computing-with-go/ch04-the-restful-web.md#a-simple-web-server
[notes/server]: https://github.com/trueheart78/book-notes/blob/master/distributed-computing-with-go/ch04-the-restful-web.md#the-rest-server-for-books-api
[notes/curl]: https://github.com/trueheart78/book-notes/blob/master/distributed-computing-with-go/ch04-the-restful-web.md#how-to-make-rest-calls
[notes/client]: https://github.com/trueheart78/book-notes/blob/master/distributed-computing-with-go/ch04-the-restful-web.md#nethttp
