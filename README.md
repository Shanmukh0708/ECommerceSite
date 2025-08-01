
# 🥕 Farmer’s Market

A dynamic web platform built using Django and modern frontend technologies to enhance interaction between local farmers, vendors, and customers. The system provides real-time updates on market events, vendor availability, and product listings — empowering rural commerce through technology.

---

## 🚀 Features

- **Responsive UI**: Mobile-friendly and accessible layout for both vendors and customers.
- **Vendor Dashboard**: Allows vendors to register, log in, and manage their products and profiles.
- **Real-Time Listings**: Admin can post updates on market events, promotions, or seasonal product arrivals.
- **Product Management**: Add, update, and remove farm produce with details such as price, quantity, and category.
- **Secure Authentication**: Role-based login system for Admin and Vendors.
- **Admin Panel**: Manage users, approve vendor applications, and monitor platform activity.

---

## 🛠️ Tech Stack

| Layer         | Technologies Used                        |
|--------------|-------------------------------------------|
| Frontend     | HTML5, CSS3, JavaScript                   |
| Backend      | Django (Python)                           |
| Database     | SQLite (default with Django)              |
| Authentication | Django’s built-in auth system          |

---

## 📂 Project Structure

```
farmers_market/
├── market/                 # Main application
│   ├── migrations/
│   ├── static/             # CSS/JS files
│   ├── templates/          # HTML templates
│   ├── admin.py
│   ├── models.py
│   ├── views.py
│   └── urls.py
├── farmers_market/         # Project settings
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── manage.py
```

---

## 📸 Screenshots

> *(Add screenshots of homepage, admin dashboard, vendor panel here)*

---

## 🔐 Authentication Flow

- Vendor Registration → Pending Approval (by Admin)
- Once approved → Vendor logs in and manages their product listings
- Admin login → Full access to dashboards and content control

---

## 📦 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/farmers-market.git
   cd farmers-market
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Run the server**
   ```bash
   python manage.py runserver
   ```

6. **Create a superuser (for admin panel)**
   ```bash
   python manage.py createsuperuser
   ```

7. Visit `http://127.0.0.1:8000/` in your browser.

---

## 🙋‍♂️ Use Cases

- Promote direct-to-customer local agriculture sales
- Digitally onboard small-scale farmers and vendors
- Enable easy tracking of local market updates and product stock

---

## 📜 License

This project is licensed under the MIT License — feel free to use, modify, and share with credit.

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss your idea.

---
