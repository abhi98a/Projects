# Projects
Spring Java Backend Projects

#Project 01

TODO LIST API
Features:
-- We have **Tasks** and **Notes**

Tasks
1)We can see all existing tasks
2)We can create new tasks
  a)every task has a title, a due date, and a boolena flag "completed".
  b)Every task once created , also have a unique ID
3)A given task can be masked as completed(or undo completed too)
4)Due data of a task can changed too
5)Task can be delted too

Notes
1) Notes exists inside tasks.
2) Every note has a title and a body
  a) once a note is added, it should have an id too.
3)Multiple notes can be added into a task.



REST API'S


| entities   actions  | /tasks (collection)                                                                             | /tasks/{id} (entity)  /tasks/123                                                                                                           |   |   |
|---------------------|-------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|---|---|
| GET                 | Read all tasks                                                                                  | get details of task id 123                                                                                                                 |   |   |
| POST                | create a new task Body will contain title, due date etc   (task id will be generated by server) | NOT EXISTS  usually we do not POST requests  on individual entities                                                                        |   |   |
| PUT                 | NOT EXISTS  usually we do not PUT requests  on collections                                      | create a new task body will contain title, due data etc new task with id 123 will be created or overwritten  (task id generated by client) |   |   |
| PATCH               | NOT EXISTS  usually we do not POST requests  on collections                                     | update an existing task body can contain new title , due date ..etc                                                                        |   |   |
| DELETE              | NOT EXISTS  usually we do not DELETE requests  on collections                                   | delete task id 123                                                                                                                         |   |   |
