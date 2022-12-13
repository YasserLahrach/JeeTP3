#                                                         Jee Microservices + Angular + KeyCloak
![logoreadme](https://user-images.githubusercontent.com/55364638/206926865-496024be-f97d-44d8-af78-c3fa4c4d2e9f.png)
# I. Backend :
## 1. use case

![image](https://user-images.githubusercontent.com/62290643/206123723-0f5d7345-b23d-4ecb-84cb-83346104a73d.png)

## 2 Inventory service - get all products
```http
GET /localhost:8888/PRODUCT-SERVICE/products
```

![image](https://user-images.githubusercontent.com/55364638/206927699-da2bd3b9-7d1c-4ca3-837e-c9564a826ede.png)



## 3 Inventory service - get product by ID 
```http
GET /localhost:8888/PRODUCT-SERVICE/products/{id}
```

![image](https://user-images.githubusercontent.com/101510983/206922542-ff3bc375-78ba-4956-92f4-0cc57ac762b8.png)



## 4 Customer Service - get All Customers
```http
GET /localhost:8888/CUSTOMER-SERVICE/customers
```

![image](https://user-images.githubusercontent.com/101510983/206921889-6f2333f5-b2ac-4d27-839b-c0989720c140.png)


## 5 Customer Service - get Customer by ID
```http
GET /localhost:8888/CUSTOMER-SERVICE/customers/{id}
```

![image](https://user-images.githubusercontent.com/101510983/206922673-eb757211-bc70-4d62-a1c2-8248050f3133.png)


## 6 Bill Service - get bills
```http
GET /localhost:8888/BILLING-SERVICE/fullbills
```

![image](https://user-images.githubusercontent.com/101510983/206922042-3f83dfcb-cb8e-4227-ae03-b5013cbf62f5.png)


## 7 Bill Service - get bill by id
```http
GET /localhost:8888/BILLING-SERVICE/fullbills/{id}
```

![image](https://user-images.githubusercontent.com/101510983/206922866-21e9873d-ca97-4434-8cf6-57dfcaadc571.png)


## 8 Eureka Service 
```http
GET /localhost:8761/
```

![image](https://user-images.githubusercontent.com/101510983/206922145-5a50d39f-704c-4ca9-a1cc-ed65cbd20569.png)

# II. Frontend Angular Client :
## Login screen 

![image](https://user-images.githubusercontent.com/101510983/206923607-8e842b94-d208-4dc6-8cbe-fb68db9037ec.png)

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
![WhatsApp Image 2022-12-13 at 09 19 11](https://user-images.githubusercontent.com/101005117/207266996-5e025253-895a-4d6c-b9da-fb4435c3d527.jpeg)


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

![Screen Shot 2022-12-13 at 09 34 08](https://user-images.githubusercontent.com/101005117/207266057-7cf2d644-c4f4-462d-a4e0-284f5688fbba.jpg)
![Screen Shot 2022-12-13 at 09 33 43](https://user-images.githubusercontent.com/101005117/207266081-1c17b46b-a9db-4359-af07-5e266a69c163.jpg)
![Screen Shot 2022-12-13 at 09 32 48](https://user-images.githubusercontent.com/101005117/207266091-c5b9f707-92ba-4bb8-80ba-c55752ed0150.jpg)
![Screen Shot 2022-12-13 at 09 31 00](https://user-images.githubusercontent.com/101005117/207266095-06a415f3-8919-439b-9c61-edc7f6809f02.jpg)
![Screen Shot 2022-12-13 at 09 30 56](https://user-images.githubusercontent.com/101005117/207266099-474e1f88-cb22-4dba-8fa2-448df994c7b0.jpg)
![Screen Shot 2022-12-13 at 09 30 13](https://user-images.githubusercontent.com/101005117/207266112-6ef2a2f2-0daf-4e15-9ff8-71d88da8b672.jpg)
![Screen Shot 2022-12-13 at 09 29 46](https://user-images.githubusercontent.com/101005117/207266118-41f3b18e-3aaf-4c81-9edc-a3bd6941b4e2.jpg)
![Screen Shot 2022-12-13 at 09 26 58](https://user-images.githubusercontent.com/101005117/207266122-1cfe7ce3-f204-46dd-b947-cdd771f1fcb8.jpg)
![Screen Shot 2022-12-13 at 09 26 53](https://user-images.githubusercontent.com/101005117/207266125-36c8e11b-a790-4bf4-9560-42ffd0f8c518.jpg)
![Screen Shot 2022-12-13 at 09 26 49](https://user-images.githubusercontent.com/101005117/207266129-8a7ea3ea-6918-40da-be08-01bca98ade24.jpg)
![Screen Shot 2022-12-13 at 09 26 12](https://user-images.githubusercontent.com/101005117/207266133-485f61b3-6621-4ea1-a6bf-4fa5571a1e3a.jpg)
![Screen Shot 2022-12-13 at 09 25 49](https://user-images.githubusercontent.com/101005117/207266135-32d12350-4f92-4e65-8f74-fae3d5390480.jpg)
![Screen Shot 2022-12-13 at 09 25 42](https://user-images.githubusercontent.com/101005117/207266141-3ef301cf-a782-45c8-bae1-9d8360f9af82.jpg)
![Screen Shot 2022-12-13 at 09 25 31](https://user-images.githubusercontent.com/101005117/207266144-6f8e1737-ef3f-4f9a-b332-b8003cc06dc3.jpg)
![Screen Shot 2022-12-13 at 09 25 11](https://user-images.githubusercontent.com/101005117/207266149-1b78e089-c095-49a1-a25a-5bfe7259204e.jpg)
![Screen Shot 2022-12-13 at 09 24 53](https://user-images.githubusercontent.com/101005117/207266166-a9140c13-98fd-40d5-a879-9a0988806896.jpg)
![Screen Shot 2022-12-13 at 09 24 40](https://user-images.githubusercontent.com/101005117/207266168-b6531c30-0752-443d-9f2e-7dffab642c0e.jpg)
![Screen Shot 2022-12-13 at 09 24 31](https://user-images.githubusercontent.com/101005117/207266176-d3f25238-3d0f-43f7-9599-50e71094f388.jpg)
![Screen Shot 2022-12-13 at 09 24 08](https://user-images.githubusercontent.com/101005117/207266184-891839b2-9e02-4698-807a-55e2b0448ca3.jpg)
![Screen Shot 2022-12-13 at 09 24 02](https://user-images.githubusercontent.com/101005117/207266191-f246f1d8-65fe-465c-98a5-ff8756bf1b7e.jpg)
![Screen Shot 2022-12-13 at 09 22 42](https://user-images.githubusercontent.com/101005117/207266197-1d5e0034-44e0-49f2-a617-624fa3f2a27b.jpg)
![Screen Shot 2022-12-13 at 09 22 35](https://user-images.githubusercontent.com/101005117/207266200-bd5e8142-7c5d-4d19-b6e9-5f0e4b7a5441.jpg)
![Screen Shot 2022-12-13 at 09 22 31](https://user-images.githubusercontent.com/101005117/207266205-717e1bc8-cace-4f95-99d4-cbb789e6db78.jpg)
![Screen Shot 2022-12-13 at 09 22 20](https://user-images.githubusercontent.com/101005117/207266210-eb388c7d-8281-4d21-b9a3-16e6df3085e6.jpg)
![Screen Shot 2022-12-13 at 09 22 05](https://user-images.githubusercontent.com/101005117/207266217-95368e66-db31-4c4e-8a36-cfde4b9654d8.jpg)
![Screen Shot 2022-12-13 at 09 21 19](https://user-images.githubusercontent.com/101005117/207266218-6f4ce590-bfca-4cab-93af-3677a54ac722.jpg)
![Screen Shot 2022-12-13 at 09 14 59](https://user-images.githubusercontent.com/101005117/207266222-b9e07427-eb60-4643-804f-aa7dd2b1fa7c.jpg)
![Screen Shot 2022-12-13 at 09 13 49](https://user-images.githubusercontent.com/101005117/207266225-2bd94e4d-933a-415f-a0e0-ad9270573923.jpg)
![Screen Shot 2022-12-13 at 09 13 38](https://user-images.githubusercontent.com/101005117/207266227-5b2591f5-a5a4-4646-b020-01c1c9c1fa96.jpg)
![Screen Shot 2022-12-13 at 09 13 22](https://user-images.githubusercontent.com/101005117/207266230-d053e7f6-c0ae-4de0-8d81-65360720e044.jpg)
![Screen Shot 2022-12-13 at 09 12 57](https://user-images.githubusercontent.com/101005117/207266235-8cfb8758-4f60-4641-97be-45f83fe3d108.jpg)
![Screen Shot 2022-12-13 at 09 12 36](https://user-images.githubusercontent.com/101005117/207266239-29a70438-3520-4c5f-95f8-17d5d8186335.jpg)

![WhatsApp Image 2022-12-13 at 09 17 58](https://user-images.githubusercontent.com/101005117/207267389-c09da31f-1c64-464a-b538-e3cfaf0e24f7.jpeg)
![WhatsApp Image 2022-12-13 at 09 19 11](https://user-images.githubusercontent.com/101005117/207267401-91de2af7-772d-4e1d-bb6a-42dfbf4af35d.jpeg)
