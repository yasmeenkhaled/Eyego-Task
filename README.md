# Eyego-Task

## Steps :
- ## Create a simple web app (Node.js) with an API returning Hello Eyego
  
   -first install npm init that using to create package.json
   - instaall npm install express using to express framework
     
> $ npm init -y
>
> $ npm install express
>
> node index.js

### That will Runn in Port localhost 3000

![image](https://github.com/user-attachments/assets/d8574b86-b1e4-4b68-93d8-57cffe14e04a)


- ## Write a Dockerfile
  
   - expose at port 3000

- Steps :

  > $ docker build -t eyego .
  >
  > $ docker run -d -p 3000:3000 eyego

  
 ![image](https://github.com/user-attachments/assets/d0055c1d-8978-439f-a409-5c112cb423e3)

