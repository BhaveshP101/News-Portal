# 📰 News Portal

A full-stack **News Portal web application** built using **Python and Django**.  
The platform allows users to browse news, search for articles, view news by category, comment on posts, and manage profiles. It also includes an administration system for managing news, categories, comments, and sub-admins.

## 🚀 Features

### 👤 User Features
- User registration and login
- User profile management
- Change password
- Browse latest news
- Search news articles
- View news by category
- View detailed news articles
- Comment on news articles
- Contact Us page

### 🛠️ Admin Features
- Admin dashboard
- Add, update, and manage news posts
- Create and manage categories
- Create and manage subcategories
- Manage comments
- Approve or reject comments
- Add and manage sub-admins
- Manage website content
- View and update profiles

### 📱 UI Features
- Responsive web interface
- News listing and detail pages
- Category-based navigation
- Rich text editor integration
- Interactive charts and UI components
- Static assets including CSS, JavaScript, images, icons, and fonts

## 🛠️ Technologies Used

### Backend
- Python
- Django

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap

### Database
- SQLite / MySQL configuration supported by the project

### Other Tools & Libraries
- TinyMCE
- Chart.js
- ApexCharts
- ECharts
- Bootstrap Icons
- Font Awesome
- Remix Icon

## 📂 Project Structure

```text
news-portal-django/
│
├── manage.py
├── requirements.txt
├── .gitignore
│
├── newsapp/
│   ├── admin.py
│   ├── apps.py
│   ├── context_processors.py
│   ├── migrations/
│   ├── models.py
│   ├── tests.py
│   └── views.py
│
├── onps/
│   ├── settings.py
│   ├── urls.py
│   ├── views.py
│   ├── adminviews.py
│   ├── subadminviews.py
│   ├── asgi.py
│   └── wsgi.py
│
├── static/
│   ├── assets/
│   └── assets1/
│
└── templates/
    ├── admin/
    ├── includes/
    ├── includes1/
    └── *.html
