# Full-Stack Blog Project

This is a full-stack blog application built with:

- **Frontend:** [Next.js](https://nextjs.org/)
- **Backend:** [Django](https://www.djangoproject.com/) & [Django REST Framework](https://www.django-rest-framework.org/)

## 📁 Project Structure

```
Blog Project/
├── blog_backend/      # Django backend (REST API)
└── blog_frontend/     # Next.js frontend (React-based)
```

---

## 🚀 Getting Started

### 🔧 Backend Setup (Django + DRF)

1. Navigate to the backend folder:

   ```bash
   cd blog_backend
   ```

2. Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install required packages:

   ```bash
   pip install django djangorestframework
   ```

4. Start the Django project (if not already):

   ```bash
   django-admin startproject config .
   ```

5. Run the development server:

   ```bash
   python manage.py runserver
   ```

---

### 🖥️ Frontend Setup (Next.js)

1. Navigate to the frontend folder:

   ```bash
   cd blog_frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the development server:

   ```bash
   npm run dev
   ```

---

## 📌 Features (Planned)

- User authentication (JWT)
- Create, edit, delete blog posts (Admin/Editor roles)
- View blog posts (Public)
- Comment system

---

## 📦 Tech Stack

| Layer    | Technology              |
|----------|-------------------------|
| Frontend | Next.js, React, Tailwind |
| Backend  | Django, Django REST Framework |
| Auth     | JWT (SimpleJWT or similar) |
| DB       | SQLite (for dev), PostgreSQL (for prod) |

---

## 📄 License

This project is licensed under the MIT License.

---

## ✍️ Author

Built with ❤️ by [َِAnis Harkat]