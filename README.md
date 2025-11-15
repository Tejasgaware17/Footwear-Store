# 🛍️ Footwear Store — Full-Stack Django E-Commerce Web App

A complete e-commerce platform for browsing, filtering, and purchasing footwear products. Built using **Django**, **Python** and **Sqlite3 DB**, this project was developed as a team project, with responsibilities including UI design, backend development, database architecture, feature development, and integration of core e-commerce flows.

---

## 📖 About the Project

**Footwear Store** is a functional e-commerce web application built to demonstrate real-world full-stack development skills. The platform allows users to browse footwear products, filter them, add items to cart, manage multiple delivery addresses, and place orders securely.

The project also includes an **admin panel**, **QR-code based order verification**, and **payment-gateway integration**, offering a well-rounded, production-style experience.

---

## ✨ Features

### 👤 User Features

* User registration & login
* Password reset functionality
* Manage multiple delivery addresses
* Browse and filter footwear products
* Add/remove items from cart and update quatities
* Checkout flow with payment-gateway integration
* View order history
* Order verification using QR code

### 🛠️ Admin Features

* Add / edit / delete products
* Manage categories
* View and manage orders
* Admin dashboard for managing backend data

---

## 🧱 Tech Stack

**Frontend:**

* HTML5, CSS3, Bootstrap

**Backend:**

* Python, Django

**Database:**

* SQLite3

**Other Tools:**

* Django Admin (Jazzmin)
* Payment Gateway Integration

---

## 📁 Project Structure (Simplified)

```
Footwear-Store/
├── manage.py
├── app/                   # App for products, cart, orders
    ├── templates/         # HTML templates
    ├── static/app         # CSS, JS, images
    └── other files..
├── requirements.txt
├── .gitignore
└──  media/product         # Uploaded images
```

---

## ⚙️ Installation & Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Tejasgaware17/Footwear-Store.git
   ```

2. **Navigate into the project:**

   ```bash
   cd Footwear-Store
   ```

3. **Create and activate a virtual environment:**

   ```bash
   python -m venv env
   source env/bin/activate   # Linux/Mac
   env\Scripts\activate     # Windows
   ```

4. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```
   
5. **Run migrations:**

   ```bash
   python manage.py migrate
   ```

6. **Start the development server:**

   ```bash
   python manage.py runserver
   ```

7. Open the website at:

   ```
   http://127.0.0.1:8000/
   ```

8. You can add static images for the sections of the wesite as all static images are not present.

---

## ⭐ Support

If you find this project useful:

* ⭐ Star the repository
* 💬 Share feedback or suggestions
* 🔁 Fork and build upon it

---

Built with ❤️ using Django.
