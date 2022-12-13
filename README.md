#                                                         Jee Microservices + Angular + KeyCloak
![logoreadme](https://user-images.githubusercontent.com/55364638/206926865-496024be-f97d-44d8-af78-c3fa4c4d2e9f.png)
# I. Backend :
## 1. use case
![WhatsApp Image 2022-12-13 at 09 17 58](https://user-images.githubusercontent.com/101005117/207267389-c09da31f-1c64-464a-b538-e3cfaf0e24f7.jpeg)
![WhatsApp Image 2022-12-13 at 09 19 11](https://user-images.githubusercontent.com/101005117/207267401-91de2af7-772d-4e1d-bb6a-42dfbf4af35d.jpeg)

## 2 Inventory service - get all products
```http
localhost:8888/PRODUCT-SERVICE/products
```

![Screen Shot 2022-12-13 at 09 12 57](https://user-images.githubusercontent.com/101005117/207266235-8cfb8758-4f60-4641-97be-45f83fe3d108.jpg)


## 3 Inventory service - get product by ID 
```http
localhost:8888/PRODUCT-SERVICE/products/{id}
```

![Screen Shot 2022-12-13 at 09 13 49](https://user-images.githubusercontent.com/101005117/207266225-2bd94e4d-933a-415f-a0e0-ad9270573923.jpg)


## 4 Customer Service - get All Customers
```http
localhost:8888/CUSTOMER-SERVICE/customers
```

![Screen Shot 2022-12-13 at 09 13 22](https://user-images.githubusercontent.com/101005117/207266230-d053e7f6-c0ae-4de0-8d81-65360720e044.jpg)

## 5 Customer Service - get Customer by ID
```http
localhost:8888/CUSTOMER-SERVICE/customers/{id}
```

![Screen Shot 2022-12-13 at 09 13 38](https://user-images.githubusercontent.com/101005117/207266227-5b2591f5-a5a4-4646-b020-01c1c9c1fa96.jpg)

## 6 Bill Service - get bills
```http
localhost:8888/BILLING-SERVICE/fullbills
```

![Screen Shot 2022-12-13 at 09 14 59](https://user-images.githubusercontent.com/101005117/207266222-b9e07427-eb60-4643-804f-aa7dd2b1fa7c.jpg)

## 7 Bill Service - get bill by id
```http
localhost:8888/BILLING-SERVICE/fullbills/{id}
```

![Screen Shot 2022-12-13 at 09 21 19](https://user-images.githubusercontent.com/101005117/207266218-6f4ce590-bfca-4cab-93af-3677a54ac722.jpg)

## 8 Eureka Service 
```http
localhost:8761/
```

![Screen Shot 2022-12-13 at 09 22 05](https://user-images.githubusercontent.com/101005117/207266217-95368e66-db31-4c4e-8a36-cfde4b9654d8.jpg)

# II. Frontend Angular Client :
## Login screen 

![Screen Shot 2022-12-13 at 09 22 20](https://user-images.githubusercontent.com/101005117/207266210-eb388c7d-8281-4d21-b9a3-16e6df3085e6.jpg)

## Products
## 1 Show all products 

![image](https://user-images.githubusercontent.com/55364638/206925608-0b8e8b90-f8cf-45af-987a-550ffeb810e3.png)

## 2 Edit products 

![image](https://user-images.githubusercontent.com/101510983/206923795-26a19423-e941-4acd-878e-8a0ce1e3df11.png)

## 3 Delete products 

![image](https://user-images.githubusercontent.com/55364638/206925748-42a715d1-4713-45a3-889a-ccb3ca042ca5.png)

![image](https://user-images.githubusercontent.com/55364638/206925764-23a250e5-8a39-4293-b96c-575a22dfe68b.png)


## 4 Search for a product

![image](https://user-images.githubusercontent.com/55364638/206925802-0b184999-ccb0-4a54-9fc9-dcf419205f83.png)


## 5 New Product

![image](https://user-images.githubusercontent.com/55364638/206925875-db2771c4-e4b0-4970-8f5d-e7c699a9b4ee.png)

![image](https://user-images.githubusercontent.com/55364638/206925899-ebcd1e02-dfbe-43f0-b0ca-e52d264c84a9.png)

## Products
## 1 Show all customer

![image](https://user-images.githubusercontent.com/55364638/206925644-39d57c48-dd68-4d57-a563-a76e20dabe65.png)



## 2 Edit Customer

![image](https://user-images.githubusercontent.com/101510983/206924228-151e1ed2-e1d6-406d-8849-34da1dc34937.png)


## 3 Delete Customer 

![image](https://user-images.githubusercontent.com/55364638/206926221-6b3c8033-4f51-420a-89eb-9634b8322d2b.png)



## 4 Search Customer 

![image](https://user-images.githubusercontent.com/55364638/206926003-7e101bb2-764a-4083-8270-739fa6e95709.png)



## 5 New Customer 

![image](https://user-images.githubusercontent.com/55364638/206925953-153464e1-a35e-470b-ad44-9cf09874aa25.png)


![image](https://user-images.githubusercontent.com/55364638/206925982-3003c687-4601-4ee2-b88c-f0b2b58dcf3e.png)


## Bills
## Show Bills  

![image](https://user-images.githubusercontent.com/55364638/206925572-719bdaa5-0195-46e8-b4e2-7a190a300df9.png)


# III Secured Angular Client with keycloak 
## 1 Setup
![image](https://user-images.githubusercontent.com/55364638/206931547-ea2548af-8dd5-4a6d-9906-912f9330fe16.png)


## 2 Postman
![image](https://user-images.githubusercontent.com/46407388/206116789-117ba8a2-f337-4fa4-9e01-5d34998c82e5.png)


## 3 Refresh Token
![image](https://user-images.githubusercontent.com/46407388/206116912-121fab06-38fc-4e4b-81ee-cb8013bd2ff1.png)


## 4 Client Auth Credentials
![image](https://user-images.githubusercontent.com/46407388/206117029-7f95a0d9-d7d1-453d-8b0b-8b157098d418.png)

