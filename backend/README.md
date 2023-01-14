# nodejscafe
A full-working restaurant application, using nodejs and MySql and Express


1- Package installation<br>
We need to install angular for the frontend!<br>
npm install -g @angular/cli


2- .Env file content<br>
//Server<br>
PORT = 8080<br>

//Connection<br>
DB_PORT = 3306<br>
DB_HOST = localhost<br>
DB_USERNAME = root<br>
DB_PASSWORD = password<br>
DB_NAME = cafenodejs<br>

ACCESS_TOKEN = token<br>

3- How to generate token<br>
in terminal type node<br>
then<br>
require('crypto').randomBytes(64).toString('hex')<br>

4- How to install a package<br>
npm install --save jasonwebtoken nodemailer <br>


5- Useful website for development<br>
jwt.io<br>
postman.com<br>


productDetails example for running API<br>
[{\"id\": 1, \"name\": \"Black Coffe\", \"price\": 99, \"total\": 99, \"category\": \"Coffee\", \"quantity\": \"1\"}]<br>
