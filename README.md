# A REST API With Node, Express, TypeScript & MongoDB + Authentication

This project demonstrates a **RESTful API** built with **Node.js**, **Express**, **TypeScript**, and **MongoDB**, featuring user authentication and CRUD operations.
It was developed to practice backend architecture, authentication flows, database integration, and API testing using **Restfox**.

---

## 🚀 Features

* Built with **Node.js** and **Express**
* Written in **TypeScript**
* Database: **MongoDB**
* Authentication (login & register endpoints)
* CRUD operations for data management
* API testing with **Restfox**

## 📌 Overview

The API allows users to:

* Register and log in securely with JWT authentication
* Perform CRUD operations on stored data
* Connect to a **MongoDB** database
* Test endpoints easily using Restfox

---

## ⚙️ Project Setup

```bash
git clone https://github.com/username/repository-name.git
cd repository-name
npm install
npm run dev
```

Server runs at:
`http://localhost:8000`

---

## 📂 Project Structure

```
src/
 ┣ controllers/   → Business logic for routes
 ┣ middleware/    → Authentication & validation
 ┣ models/        → Mongoose schemas
 ┣ routes/        → API endpoints
 ┗ server.ts      → Main application entry
```

---

## 🔑 Authentication Flow

1. **Register** → Create a new user with encrypted password.
2. **Login** → Authenticate and receive a token.
3. **Use Token** → Access protected routes (CRUD operations).

---

## 📸 Project in Action

### 1. Register a New User with Restfox

![Register Restfox](images/01_register_restfox.png)

### 2. User Saved in MongoDB

![Register MongoDB](images/02_register_mongodb.png)

### 3. Wrong Login Attempt

![Wrong Login Restfox](images/03_wrongLogin_restfox.png)

### 4. Correct Login – Token Returned

![Correct Login Restfox](images/04_correctLogin_restfox.png)

### 5. Login with Cookies Stored

![Correct Login Cookies](images/05_correctLogin_cookies_restfox.png)

### 6. Get All Users (Authorized Request)

![Get Users Restfox](images/06_getUsers_restfox.png)

### 7. Register Another User via Restfox

![Another Register Restfox](images/07_anotherOneRegister_restfox.png)

### 8. Verify Second User in MongoDB

![Another Register MongoDB](images/08_anotherOneRegister_MongoDB.png)

### 9. Fetch Users Again

![Get Users Again](images/09_tryagain_getUsers_restfox.png)

### 10. Delete a User – Restfox

![Delete User Restfox](images/10_deleteUser_restfox.png)

### 11. Verify User Deleted – MongoDB

![Delete User MongoDB](images/11_deleteUser_mongoDB.png)

### 12. Fetch Users After Deletion

![Get After Delete](images/12_get_after_deleteUser_restfox.png)

### 13. Register One More User

![Register Again](images/13_register_oneMore_restfox.png)

### 14. Get Users – Restfox

![Get Users](images/14_get_restfox.png)

### 15. Try Deleting Without Login (Unauthorized)

![Delete Without Login](images/15_delete_withoutLogin_restfox.png)

### 16. Login Again

![Login Again](images/16_login_restfox.png)

### 17. Delete User With Login (Authorized)

![Delete With Login](images/17_delete_withLogin_restfox.png)

### 18. Update User Information

![Update Restfox](images/18_update_restfox.png)

### 19. Verify Updated Data in MongoDB

![MongoDB After Update](images/19_mongoDB_afterUpdate.png)

---

## 🛠️ Technologies Used

* **Node.js** & **Express**
* **TypeScript**
* **MongoDB** & **Mongoose**
* **JWT Authentication**
* **Restfox**

---

## 📌 Conclusion

This project shows how to build a **secure REST API** with authentication, database operations, and clean TypeScript code.
The screenshots illustrate the full flow — from registration to login, CRUD operations, and database verification.

It can be extended with:

* Role-based authorization
* Advanced input validation
* Deployment on platforms like AWS, Render, or Docker
