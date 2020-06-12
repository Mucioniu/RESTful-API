# RESTful-API

This is the solution for the Engineering Back-end Internship Assessment from 2checkout. The problem was solved with NODE.js

As database, I used MongoDB Atlas, the free version, where I created a cluster and connected to my application. To use my solution you will need to create a cluster on MongoDB and put your password from your cluster in my program in "nodemon.json" 
{
    "env": {
        "MONGO_ATLAS_PW": "YOUR_MONGO_USER_PW"
    }
}

I created a route for products, and 4 http words, like GET, POST, PATCH and DELETE that manipulates the product's fields:Id, Name, Price, Category, CreatedDate, UpdatedDate. To test how they works, I used Postman application. 
For the second task I used route user that cand sing up and then sign in. The sing up function cand recognize if it's an email or not or if it's already exist. The login function use a token generated by the sign up function, token which encode the user's password. People which are not sign in can't use certain functions such as Post or Delete.
Unfortunate I couldn't solve the third task.

I used Visual Studio 2019 and some packages have been intalled in the command line throughout the assessment. The order is:
1. npm -install --save express
2. npm install --save-dev nodemon
3. npm install --save morgan
4. npm install --save body-parser
5. npm install --save mongoose
6. npm install bcrypt --save
7. npm install jsonwebtoken --save

It shouldn't affect the results, but if some errors occurs they should be in need. To start the server just simply write in command line npm start.
I hope you this program fits the requirments for the intership, I will look forward for future emails from the company with the results and feedback
