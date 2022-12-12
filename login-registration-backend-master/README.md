# API RESTful

Aplicação para cadastrar e fazer login de usuários.


- [x] Spring Boot
- [x] Spring Security
- [x] Java Mail
- [x] Verificação de email com expiração
- [x] Spring Boot

## Diagrama
![Screenshot 2021-01-13 at 23 38 08](https://user-images.githubusercontent.com/40702606/104789980-15581a00-578e-11eb-998d-30f2e6a9f461.png)

## Verificação de email com expiração
![Screenshot 2021-01-13 at 23 37 33](https://user-images.githubusercontent.com/40702606/104789893-0c674880-578e-11eb-939a-2a1cd3a8dfd2.png)

## Exemplo de requisições
### Postman
![Screenshot 2021-01-13 at 23 37 57](https://user-images.githubusercontent.com/40702606/104790087-7a137480-578e-11eb-8141-307a8850c39e.png)

### CURL
```
curl --location --request POST 'localhost:8080/api/v1/registration' \
--header 'Content-Type: application/json' \
--data-raw '{
    "firstName": "Amigos",
    "lastName": "Code",
    "email": "hellow@amigoscode.com",
    "password": "password"
}'
```
