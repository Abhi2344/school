# My Custom Frappe App - Student Management

## 📌 Description
This project is a simple Frappe application that manages student information.  
It demonstrates the creation of a custom Doctype and record management.

## ⚙️ System Requirements
- Python 3.10+
- Node.js 16+
- MariaDB / MySQL
- Redis
- Frappe Framework v15

## 🪜 Setup Instructions
```bash
# 1. Install Frappe Bench
pip install frappe-bench

# 2. Initialize bench and site
bench init my-bench --frappe-branch version-15
cd my-bench
bench new-site mysite.localhost

# 3. Get the app
bench get-app https://github.com/<your-username>/my_custom_app.git

# 4. Install app on site
bench --site mysite.localhost install-app my_custom_app

# 5. Start the server
bench start
