# 🍽️ Online Menu App

A simple Django web application for displaying a restaurant menu.  
Built with **Django** and styled using **Bootstrap 5**.

---

## ✨ Features
- 📋 View categorized meals (e.g., Breakfast, Lunch, Dinner).
- 📝 Each menu item has:
  - Name
  - Description
  - Price
  - Status (available / unavailable — unavailable items are shown with a strikethrough).
- 🔎 Individual detail page for each menu item.
- 🛠️ Django Admin integration to manage menu items:
  - Add / edit / delete meals
  - Filter items by status
  - Search items by name or description

---

## 🖼️ Screenshots
- **Home Page (Menu List)**  
  Displays all menu items grouped by meal type.<br>
  <img width="1873" height="965" alt="main" src="https://github.com/user-attachments/assets/55cdef92-ec85-4595-a488-f543b914e2ee" />


- **Menu Item Detail Page**  
  Shows detailed information about a selected dish.<br>
  <img width="1835" height="737" alt="item" src="https://github.com/user-attachments/assets/c0358f47-4d5a-49b1-94e2-2a45a993a285" />

## There is also a QR generated that leads the user to the menu 
<img width="323" height="326" alt="image" src="https://github.com/user-attachments/assets/6cbcdae5-911c-4686-997e-5a5a2a35c2b1" />
<br><br>
---

## 🏗️ Tech Stack
- **Backend:** Django (Class-based views: `ListView`, `DetailView`)
- **Frontend:** HTML, Bootstrap 5, Django Templates
- **Database:** SQLite (default, can be swapped for PostgreSQL/MySQL)
- **Admin Panel:** Django Admin
