# Backend Todo-List usando Spring Boot / Todo-List Backend using Spring Boot

Deploy feito com a Render => https://todolistspringboot-yjqc.onrender.com<br/>

Projeto do Mini Curso Java - Rocketseat<br/>

This project consists of using Java and Spring Boot to create the controller API of a ToDo-List<br/>

To test, use the deploy link below:<br/>
https://todolistspringboot-yjqc.onrender.com<br/>
in some REST request tool, for example, API Dog; Insomnia or Postman.<br/>

Register user:<br/>
[POST] deployLink/users/<br/>
JSON Content:<br/>
{<br/>
  "name": "Ilton Dev",<br/>
  "username": "iltondev",<br/>
  "password": "070904"<br/>
}<br/>
![Captura de tela 2024-04-24 155039](https://github.com/iltoncavalcante/todoListSpringBoot/assets/131810687/517c61f6-b3b8-494a-912d-a7dc521b2170)
Register task:<br/>
[POST] deployLink/tasks/<br/>
JSON Content:<br/>
{<br/>
  "description":"Task to program more",<br/>
  "title":"Task",<br/>
  "priority":"HIGH",<br/>
  "startAt":"2024-10-06T12:30:00",<br/>
  "endAt":"2024-10-06T15:35:00"<br/>
}<br/>
Use Auth Basic and enter the username and password<br/>
![Captura de tela 2024-04-24 155056](https://github.com/iltoncavalcante/todoListSpringBoot/assets/131810687/c0c061b6-5a8c-4750-8259-d16cd6ea66e0)
List Task:<br/>
[GET] deployLink/tasks/<br/>
Use Auth Basic and enter the username and password<br/>
![Captura de tela 2024-04-24 155110](https://github.com/iltoncavalcante/todoListSpringBoot/assets/131810687/214415b0-e01d-45c0-aa24-306c0c10611a)
Update task:<br/>
[PUT] deployLink/tasks/idTask<br/>
JSON Content:<br/>
{<br/>
  "description":" ",<br/>
  "title":" ",<br/>
  "priority":" ",<br/>
  "startAt":"2024-10-06T12:30:00",<br/>
  "endAt":"2024-10-06T15:35:00"<br/>
}
Use Auth Basic and enter the username and password<br/>
#You can choose only one item to update in the task<br/>
![Captura de tela 2024-04-24 155126](https://github.com/iltoncavalcante/todoListSpringBoot/assets/131810687/cb1ed7f5-6167-49a9-855a-7b74ae93feb4)
![Captura de tela 2024-04-24 155143](https://github.com/iltoncavalcante/todoListSpringBoot/assets/131810687/03615b37-cdda-4208-beed-088d108b1e61)






