# Auth-express-jwt-mongodb

Backend only

Simplified Express app with jwt verification and data is stored in mongo db 

user postman for requests

## Features
- **Sign Up**: Register users
- **Sign In**: Authenticate and get JWTs
- **Get User Info**: Retrieve user details

## Usage
1. Clone: `git clone https://github.com/-Singh02/express-mongo.git`
2. Install: `npm install`
3. Run: `node index.js`


**POST /signup**
```json
{ 
    "username": "gurvinder", 
    "password": "yourpassword", 
}
```

**POST /signin**
```json
{ 
    "username": "gurvinder", 
    "password": "yourpassword" 
}
```

**Get /me**
- Include header: `token: the output you get in signin`

**POST /todo**
- Include header: `token: the output you get in signin`
```json
{ 
    "title": "commplete thi s", 
    "done": false 
}
```

**GET /todos**
- Include header: `token: the output you get in signin`

