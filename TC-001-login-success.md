# TC-001 – Successful Login with Valid Credentials

🗓️ Date: 2025-07-10  
👤 Tester: César  
🧪 Test Type: Functional – Positive  
📋 Status: Draft  

---

## 🎯 Objective
Verify that the user is able to log in with valid credentials.

---

## 🔍 Preconditions
- The user is on the saucedemo login page: https://www.saucedemo.com

---

## 🧾 Test Data
- **Username:** `standard_user`  
- **Password:** `secret_sauce`

---

## ▶️ Test Steps

| Step # | Action                         | Expected Result                                  |
|--------|--------------------------------|--------------------------------------------------|
| 1      | Enter `standard_user` in username field | The text is entered correctly                   |
| 2      | Enter `secret_sauce` in password field | The text is entered correctly                   |
| 3      | Click on the "Login" button    | The user is redirected to the inventory page (`/inventory.html`) |

---

## ✅ Expected Result
The user logs in successfully and is redirected to:  
`https://www.saucedemo.com/inventory.html`

---

## 📌 Postconditions
The user is now authenticated and can interact with the store.
