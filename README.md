# eCommerce--API
This Build B2B Multi-tenant eCommerce APIs. This is a Backend code which will perform various operation like Add Owner , Add Customer , Add Products , Place Order , Browse Products , View Orders.

## Details
* Here we use MongoDB database.
* In the project i have use MVC model.
* Model contain four Schemas customer , owner , products , orders.
* Controller will handle various operation like Authentication (ie Login ) , Add Owner , Add Products , Add Customer , Place Order etc.
* Routes will handle requests and route them in proper way like Owner request or customer request or Authentication request.


## Getting Started 

* First Downold the repo.
* You Need MongoDB account if you do not have any then create one. 
* After creating account copy your MongoDB url.

### Install dependencies and run the server

* Open app.js file and past your MongoDB url in the place of 'URL' in the code.
* After that Run the command:- npm install
* After that to start server run the command:- npm start 

### Input And Output

* To place request and get output we will use Postman application so you need to install Postman in your PC.
* After installing Open the link:- https://documenter.getpostman.com/view/16692305/TzzEnDu6
* This is Postman documentation of requests.
* Here you will see various requests like Add New Owner , Add New Products , Browse Products.
* First of all Add New Owner , Add New Product , Add New Customer and also add relevant JSON data as mention in the Postman documentation .
* After that you can place othe request like Order Products , Browse Products etc.


#### * Makesure you enter proper data in the request like ProductId , CustomerId , OwnerId according to your MongoDB database and Also takecare of JSON data , You need to enter JSON data same way as mention in the Postman documentation.
   

   



  
