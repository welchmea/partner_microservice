# partner_microservice

Steps to retrieve data from USDA FoodData Central API

1. import requests library 
2. Define search parameters:
      param = {query:value} <-- must use query as the key

3. Send a POST request to the following url with param
      url = https://partnermicro.herokuapp.com 
      response = requests.post(url, params=param)
 
4. print(response.json())

