# New sample app for OADP for MongoDB

* I'll note most of this was lifted from:
https://github.com/sdil/learning/blob/master/go/todolist-mysql-go/todolist.go


## Local Setup

* Get mongo running

```
docker-compose up -d --build
```

* Get the app running

```
go mod tidy
```
* Update the db for a local connection:
HERE: https://github.com/weshayutin/todolist-mongo-go/blob/master/todolist.go#L44-L48


Execute:
```
go run todolist.go
```

Initial Page should have two entries, one complete and one incomplete.


Show items in the db:  http://localhost:8081/db/todolist/



