# Go ToDo
A simple todo list API written in Go. Uses mongodb.

# To Run
- Clone into repo
- Run `go get`
- Run your local/remote mongodb instance.
- Make sure to edit `connectionString` in `middleware.go` accordingly
- Run `go run main.go` 

## Routes
- GET `/api/task/` - Get all tasks
- POST `/api/task/` - Save a task
- PUT `/api/task/{id}` - Complete a task
- PUT `/api/undoTask/{id}` - Undo a task
- DELETE `/api/deleteTask/{id}` - Delete a task
- DELETE `/api/deleteAllTask/` - Delete all tasks