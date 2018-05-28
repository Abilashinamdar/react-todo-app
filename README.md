# React Todo List App
In this repository you will find "Todo List App".
This is a application developed in React which is good for beginners to start with.
The application uses the [create-react-app](https://github.com/facebook/create-react-app) boilerplate.

This application adds, deletes and updates the todo list.
This application is combination of `React`, `Redux` and `sagas`.
You can also connect to backend microservice by specifying base URL of the server.

### Getting started
Checkout this repo, install dependencies, then start the process with the following:
```
> git clone https://github.com/Abilashinamdar/react-todo-app.git

> cd react-todo-app

> npm install or yarn

> npm start or yarn start
```



######  Note :
If you want to connect with your backend microservice, do some changes which are as follows :

```
1. In `src/utils/axios.js` at line no. 4 set the base URL (Host) of the server.

2. In `src/middlewares/api/apiService.js` at line no. 3 set the api end points of your microservice.

3. In `src/middlewares/sagas/toDoAppSaga.js` uncomment code in catch block of all the methods to handle error cases.
```
