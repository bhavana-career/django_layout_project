# Django Layout Project

## Overview

This project is a simple Django web application demonstrating **template inheritance** using a base template (`layout.html`). The layout template contains a common **header, navigation menu, and footer**, which are reused across multiple pages.

The project includes the following pages:

* Home
* About Us
* Contact Us

All pages inherit the same layout and use **CSS for styling**.

---

## Features

* Django template inheritance
* Common layout using `layout.html`
* Navigation menu for page switching
* Static CSS styling
* Multiple pages with shared structure

---

## Technologies Used

* Python
* Django
* HTML
* CSS
* Git & GitHub

---

## Project Structure

```
django_layout_project
│
├── manage.py
├── myproject
│   ├── settings.py
│   └── urls.py
│
└── website
    │
    ├── templates
    │   └── website
    │       ├── layout.html
    │       ├── home.html
    │       ├── about.html
    │       └── contact.html
    │
    ├── static
    │   └── css
    │       └── style.css
    │
    ├── views.py
    └── urls.py
```

---

## Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/bhavana-career/django_layout_project.git
```

### 2️⃣ Navigate to the project folder

```
cd django_layout_project
```

### 3️⃣ Install Django

```
pip install django
```

### 4️⃣ Run the development server

```
python manage.py runserver
```

### 5️⃣ Open the website

```
http://127.0.0.1:8000
```

---

## Screenshots

### Home Page
![Home Page](image.png)


### About Page
![About Page](image-1.png)

### Contact Page

![Contact Page](image-2.png)

---

## Author

Bhavana
