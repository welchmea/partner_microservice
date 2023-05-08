# partner_microservice

Steps to retrieve data from USDA FoodData Central API

1. import requests library

2. Define search parameters:
      param = {query:value} <-- must use 'query' as the key
      * value represents the food that the user is wanting to receive data about.
   
REQUEST DATA

3. Send a GET request to the following url with param
      url = 'http://127.0.0.1:5000'
      response = requests.get(url, params=param)
      
RECEIVE DATA
 
4. print(response.json() OR response.text will also work.

UML diagram:

![UMLmicroservice drawio](https://user-images.githubusercontent.com/107885378/236893149-4f681d66-2440-4dd0-b5e4-2008fc076788.png)





