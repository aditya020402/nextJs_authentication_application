learnings while creating the project
in the next js we have a src folder and the src folder has all the code that is required to build the application 
inside the src folder we have the app which has two parts . one is the backend part and the frontend part 
their are also other files like the models and the helpers that would be required to write the code
the backend is written in the api folder (API)
and the file name we use are route and while writting code in the frontend we call it page

we have file of middleware which is inside  the src but not inside the app directory

npx create-next-app@latest

express is not required in next js it has the app router already in it 


if we are sending some token and if we are working on the token on the server side we usually prefer the url to be domain.com/verifytoken/sometokenvalue
while we are working with client we usually like it to be domain.com/verifytoken?token=sometokenvalue 

