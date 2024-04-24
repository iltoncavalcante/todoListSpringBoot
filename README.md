# Backend Todo-List usando Spring Boot / Todo-List Backend using Spring Boot

Deploy feito com a Render => https://todolistspringboot-yjqc.onrender.com

Projeto do Mini Curso Java - Rocketseat

This project consists of using Java and Spring Boot to create the Backend of a ToDo-List

To test, use the deploy link below:
https://todolistspringboot-yjqc.onrender.com
in some REST request tool, for example, API Dog; Insomnia or Postman.

Register user:
[POST] <deployLink>/users/
JSON Content:
{
  "name": "Ilton Dev",
  "username": "iltondev",
  "password": "070904"
}

Register task:
[POST] <deployLink>/tasks/
JSON Content:
{
  "description":"Task to program more",
  "title":"Task",
  "priority":"HIGH",
  "startAt":"2024-10-06T12:30:00",
  "endAt":"2024-10-06T15:35:00"
}
Use Auth Basic and enter the username and password

List Task:
[GET] <deployLink>/tasks/
Use Auth Basic and enter the username and password

Update task:
[PUT] <deployLink>/tasks/<idTask>
JSON Content:
{
  "description":" ",
  "title":" ",
  "priority":" ",
  "startAt":"2024-10-06T12:30:00",
  "endAt":"2024-10-06T15:35:00"
}
Use Auth Basic and enter the username and password
#You can choose only one item to update in the task







