# Canvas

* Installing Packages Client
```sh
npx shadcn@latest init                                                   
npx shadcn@latest add button input dialog label select slider switch tabs
npm i axios fabric file-saver jspdf loadash uuid zustand next-auth@beta

npx auth secret
```

* Installing Packages Server
```sh
# api-gateway
npm i cors dotenv express express-http-proxy google-auth-library helmet jsonwebtoken nodemon

# upload-service
npm i cloudinary cors dotenv express helmet jsonwebtoken mongoose nodemon multer

# Design-services
npm i cors dotenv express helmet jsonwebtoken mongoose nodemon axios

# subscription-service
npm i cors dotenv express helmet jsonwebtoken mongoose nodemon
```