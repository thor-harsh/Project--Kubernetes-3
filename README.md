# Project--Kubernetes-3

<table>
  I made this project with three different pods and each have one container. First pod contains users-api second pod contains task-api and third pod contains auth-api.<br/>
  users-api is for registering the user which will communicate with auth-api which will validate the user and password and then will register the user.
  task-api is for adding task which can be added from outside the cluster i.e from the outside world.task-api communicates with auth-api and then add task.
  They are connected in this order:<br/>
  a)users-api is connected to auth-api and users api is exposed to world using service but auth-api is not accessible outside the world.
  <br/>
  b)task-api can communicate with auth-api and auth-api is also accessbile outside the world.
  <br/>
</table>

**Get ready to learn the advanced stuff of kubernetes and I learnt a lot while doing this project and hope you too.For any doubt or suggestion see you in pull request section. 
😁😂 Thanks!**
