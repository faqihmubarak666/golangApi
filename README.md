## USAGE


### Windows

./server.exe -port YOURPORT

or

double click server.exe

### Linux 

./server-linux -port YOURPORT

### MacOS

./server-macos -port YOURPORT

## Authenticate

### body to get token
"username" : "root",
"password" : "root"

use "auth-token" Header as key to use authentication and token as value

protected routes :
- /users/


## ENDPOINTS :

### url: http://localhost:5000/

---

GET /users --> list all users

POST /users --> create new user

---

GET /products --> list all products

POST /products --> create new produc

PUT /products/{id} --> edit product

---

POST /auth --> get token

---
