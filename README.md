# Local_passport_auth_service 

## 1. Chạy server

npm init -y

npm install express

node app.js

![Run Server](/public/resutls/server.png)

## 2. Test trên Postman

## a. Đăng kí 

![Register](/public/resutls/register.png)

User trên MongoDB (Register)

![User Register in MongoDB](/public/resutls/user_register_mongodb.png)

### b. Đăng nhập `/login`

![Login](/public/resutls/login.png)

User trên MongoDB (Login)

![User Login in MongoDB](/public/resutls/user_login_mongodb.png)

### c. Route bảo vệ `/profile`

Đối với trường hợp đã đăng nhập trước đó

![Proteced Route Login](/public/resutls/profile_login.png)

Đối với chưa đăng nhập

![Proteced Route Logout](/public/resutls/profile_logout.png)

### d. Đăng xuất `/logout`

![Logout](/public/resutls/logout.png)
