# 📚 Voxly – English Learning Platform

**Voxly** is an English language learning platform designed by **HKL HARMONY** using modern web technologies including Django and MySQL. It empowers learners with an interactive interface and a structured backend for managing lessons and progress.

---

### 🧰 Technologies Used

* **Backend**: Python, Django
* **Frontend**: HTML, CSS, JavaScript
* **Database**: MySQL

---

### 📂 Project Structure

* `manage.py` – Django’s CLI utility for tasks like running the server and migrations
* `voxly/` – Main Django project directory (settings, URLs, wsgi/asgi, etc.)
* `templates/` – HTML templates for the frontend interface
* `static/` – Static files like CSS, JavaScript, and images
* `app/` – Django app handling business logic (models, views, forms)
* `requirements.txt` – List of required Python packages
* `db.sqlite3` / MySQL – Project database
* `.gitignore` – Hides unnecessary files from version control (e.g., **pycache**)

---

### ⚙️ Installation

**Prerequisites:**

* Python 3.x
* MySQL Server
* pip (Python package manager)

**Steps:**

1. **Clone the repository:**

   ```bash
   git clone https://github.com/KhushiVernekar/Voxly-clone.git
   cd Voxly-clone
   ```

2. **Set up the virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate     # On Windows: venv\Scripts\activate
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Configure your database settings** in `settings.py` (replace with your own MySQL credentials):

   ```python
   DATABASES = {
       'default': {
           'ENGINE': 'django.db.backends.mysql',
           'NAME': 'your_db_name',
           'USER': 'your_username',
           'PASSWORD': 'your_password',
           'HOST': 'localhost',
           'PORT': '3306',
       }
   }
   ```

5. **Run migrations to initialize the database:**

   ```bash
   python manage.py migrate
   ```

6. **Start the development server:**

   ```bash
   python manage.py runserver
   ```

   > 💡 To run on your local network:
   > `python manage.py runserver 0.0.0.0:8000`

7. **Access the application** in your browser:
   [http://localhost:8000](http://localhost:8000)

---

### 🚀 Getting Started (Quick Commands)

| Action         | Command                                                       |
| -------------- | ------------------------------------------------------------- |
| Clone repo     | `git clone https://github.com/KhushiVernekar/Voxly-clone.git` |
| Migrate DB     | `python manage.py migrate`                                    |
| Run server     | `python manage.py runserver`                                  |
| Network access | `python manage.py runserver 0.0.0.0:8000`                     |

---
