[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/Naereen/ama)
[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)
[![GitHub forks](https://img.shields.io/github/forks/saswatamcode/go-todo.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/saswatamcode/go-todo/network/)
[![GitHub stars](https://img.shields.io/github/stars/saswatamcode/go-todo.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/saswatamcode/go-todo/stargazers/)
[![GitHub issues](https://img.shields.io/github/issues/saswatamcode/go-todo.svg)](https://GitHub.com/saswatamcode/go-todo/issues/)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

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