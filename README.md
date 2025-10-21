# Contractors Lab

This project is a simple **Flask** application that simulates working with contract and customer data.  
It contains two main routes: one for retrieving contract information and one for verifying customer existence.

---

## 📦 Routes

### `/contract/<id>`
- Returns contract information if the ID exists.
- Response code `200` with contract text if found.
- Response code `404` if not found.

### `/customer/<customer_name>`
- Checks if a customer exists in the array.
- Response code `204` if found (empty body).
- Response code `404` if not found.

---

## 🖼️ Screenshots

### ✅ Server Output
This shows successful responses for `/contract` and `/customer` routes.  
![Server output](./screenshots/server_output.png)

### 🌐 Browser Output
Example of `/contract/3` response in the browser.  
![Browser output](./screenshots/browser_output.png)

---

## 🧰 Tech Stack
- Python 3
- Flask

---
