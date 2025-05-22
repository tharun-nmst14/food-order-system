How To Setup -
Create Database food.
Run food.sql script provided in sql folder.
Go to login.php and try out our application. 
Sample user credentials can be found in users & wallet_details table.
Note -
This is not ready for PRODUCTION.
The username and password of sample users are stored in table users.
Only Customers with "Verified" status can place orders using "Cash on Delivery" option.
By default a new customer gets 2000 coins in Wallet on signing up, and a fake Credit card number & CVV number is generated and stored in SQL Table "wallet_details" with corresponding new customer's ID.
Use that Card Number & CVV while placing an order, else order won't be successful or use "Cash on delivery" option.
What's lacking? Dynamic payment(real payment system) and error reporting lacks in this project. And also one might wish for showing corresponding food item's photo and all that stuff.
