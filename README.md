# User Management REST API (Flask)

## Project Description

This project is a simple **REST API** built using **Flask** that allows you to perform basic CRUD (Create, Read, Update, Delete) operations on users.
User data is stored temporarily in memory using a Python dictionary.

---

## Features

* Add new users
* View all users
* Get a specific user by ID
* Update user details
* Delete users

---

## Technologies Used

* Python
* Flask
* JSON API

---

## Project Structure

```
project-folder/
│
├── app.py        # Main API script
└── README.md     # Documentation
```

---

## How to Run the Project

###  Install Dependencies

```bash
pip install flask
```

### Run the Server

```bash
python app.py
```

###  Open in Browser

```
http://127.0.0.1:5000/
```

---

## 📡 API Endpoints

### 🔹 Home

```
GET /
```

Response:

```
Welcome to User API!
```

---

### 🔹 Add User

```
POST /users
```

JSON Body:

```json
{
  "id": "1",
  "name": "John",
  "age": 22
}
```

---

### Get All Users

```
GET /users
```

---

### Get Single User

```
GET /users/<user_id>
```

---

### 🔹 Update User

```
PUT /users/<user_id>
```

---

### Delete User

```
DELETE /users/<user_id>
```

---

## Notes

* Data is stored in memory only.
* All data will be lost when server stops.
* No database is used in this version.

---

##Future Improvements

* Add database integration (SQLite / MongoDB)
* Add authentication
* Add input validation
* Deploy API online

---

This project is open-source and free to use.
