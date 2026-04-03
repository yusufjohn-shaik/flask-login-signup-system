# 🔐 Flask Login & Signup System

A simple and secure authentication system built using Flask.
This project allows users to register, log in, and access a protected dashboard using session management.

---

## 🚀 Features

* 📝 User Registration (Signup)
* 🔑 User Login
* 🔒 Password Security (can be extended with hashing)
* 👤 Session Management
* 📊 Protected Dashboard (only accessible after login)
* 🚪 Logout Functionality

---

## 🛠️ Tech Stack
* **Backend:** Flask (Python)
* **Frontend:** HTML, CSS
* **Other:** Jinja2 Templates
---

## 📁 Project Structure

```
project/
│── app.py
│── templates/
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   └── dashboard.html
│── static/
│   └── style.css
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

```
git clone https://github.com/your-username/flask-login-signup-system.git
```

2. Navigate to the project folder:

```
cd flask-login-signup-system
```

3. Install dependencies:

```
pip install flask
```

4. Run the application:

```
python app.py
```

5. Open in browser:

```
http://127.0.0.1:5000/
```


---

## 📌 Future Improvements

* 🔐 Add password hashing (Werkzeug / bcrypt)
* 🗄️ Database integration (SQLite / PostgreSQL)
* 📧 Email verification
* 🔁 Password reset functionality
* 🎨 Improve UI design

---

## 🤝 Contributing

Feel free to fork this repository and contribute to improve the project!

---

## 📄 License

This project is open-source and available under the MIT License.