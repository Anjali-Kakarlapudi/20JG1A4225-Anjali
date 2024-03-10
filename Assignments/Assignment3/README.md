Assignment - 3: In this assignment, you will create a RESTful API using Express.js and integrate it with MongoDB to perform CRUD operations on a database.

Steps to use the above code

1. Download the above code files and open that folder in VS Code.
2. Open the terminal and navigate to the folder where all the above code files are saved.
3. Run the following command so that all the necessary dependencies are installed into the folder:

npm install

4. After all the dependencies are installed, open a new terminal and run the following command so that MongoDB will be started in the backend:
mongod
5. Return back to the first terminal and run the following command to start the application:
nodemon run start
6. Open your Postman workspace, select the HTTP request as GET and paste this url: http://localhost:9000/books and click "Send"(This will retrieve all the data stored in the database.)
![image](https://github.com/Anjali-Kakarlapudi/20JG1A4225-Anjali/assets/92771878/d8e9480a-950f-4622-9026-0307387cac9d)

7. To post new data to the database, change the HTTP request to POST and add data in the JSON format.
![image](https://github.com/Anjali-Kakarlapudi/20JG1A4225-Anjali/assets/92771878/9037d421-0558-4dbf-b99b-ff961d509d21)

8. Then click "Send". The data is inserted into the database and you will get the following response:
![image](https://github.com/Anjali-Kakarlapudi/20JG1A4225-Anjali/assets/92771878/7c1b4037-651e-40d9-8715-e0cc21a147c2)

9. To check if the data is really inserted or not, change into GET and click "Send" again.
![image](https://github.com/Anjali-Kakarlapudi/20JG1A4225-Anjali/assets/92771878/1d30617e-5b33-401c-a7ae-29817ca60d8f)
10. To modify existing data in the database, change into PATCH and modify the url and click "Send".
![image](https://github.com/Anjali-Kakarlapudi/20JG1A4225-Anjali/assets/92771878/333a341a-3b12-44b4-b852-2424fecb9898)
11. After the data is modified, you will get the following output:
![image](https://github.com/Anjali-Kakarlapudi/20JG1A4225-Anjali/assets/92771878/984a8ec5-7eb9-4b48-be76-cc3059779d06)

12. To delete a particular data, change into DELETE, modify the url and click "Send".
![image](https://github.com/Anjali-Kakarlapudi/20JG1A4225-Anjali/assets/92771878/a494f040-2a4f-46fa-b65e-814e40afeb04)

