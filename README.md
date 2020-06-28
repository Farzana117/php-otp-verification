# php-otp-verification
##I have doveloped this website using HTML, CSS,Javascript and PHP technologies.
###I have used the text local api to send SMS OTP to the users.
####Description:
home page: Home page contains the login and registration pages in the nav bar. This is index.php file.
registration page : In registration page, there were username, password, email and contact number fields to be filled by user. I have used validations for these inputs, I have given validations for password field as it should contain atleast one small, one capital, one digit and length should be equal to 8. If the users enters any wrong details or leaves any input field empty, then it gives an alert to the user to fill all details correctly. You can find this file as register.php
-----After the successful registration the data will be saved in the data.json file as a plain text.
login page: In login page, there is an input field that asks user to enter their registered contact number, and then it sends otp to that number. If the user fills a mobile number that is not registered then it gives an alert to user to fill the registered mobile number. After it asks to verify otp number. This file is named as login.php
------After the successful otp verification, it takes the user to the welcome screen. This is saved as welcome.php file.
I have deployed this project on heroku platform.
Heroku link : https://php-otp-verification.herokuapp.com/
