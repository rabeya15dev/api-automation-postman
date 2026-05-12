# API Automation Testing Project (Postman + ReqRes API)

## 📌 Project Overview
This project contains API automation test cases created using Postman with the ReqRes API. It includes basic API testing such as authentication, CRUD operations, and negative test scenarios.

---

## ⚙️ Tools Used
- Postman
- ReqRes API (https://reqres.in/api)
- JavaScript (Postman Test Scripts)
- Environment Variables

---

## 📂 Project Content

### 🔐 Login API
- Performed login using valid credentials
- Captured authentication token from response

---

### 📦 GET User API
- Retrieved user details using user ID
- Verified first name and email from response

---

### ✏️ PUT Request
- Updated user data (name and job)
- Verified updatedAt timestamp in response

---

### 🔄 PATCH Request
- Updated single field (job)
- Verified only updated field in response

---

### ❌ Negative Test Cases
- Tested missing password scenario
- Tested invalid email format
- Verified 4xx status code responses (400, 401, 404)

---

## 🌍 Environment Variables
- Used environment variables for:
  - baseUrl
  - email
  - password
  - userId

---

## 🧪 Validations Performed
- Status code verification
- Response body validation
- Field value verification
- Token capture and reuse

---

## 📌 Note
ReqRes API is a mock API, so data is not permanently stored in the system.

---

## 👤 Author
Rabeya Bosri