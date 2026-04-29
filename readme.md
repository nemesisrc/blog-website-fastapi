📝 Full Stack Blog Website

A Feature-Rich Blogging Platform Built with Flask

> Inspired by Corey Schafer’s Flask Tutorial Series
Learn. Build. Scale.




---

🚀 Project Overview

This project is a full-stack blog web application developed using Python Flask, following and expanding upon Corey Schafer’s legendary Flask YouTube tutorial playlist.

It is designed to simulate a real-world blogging platform where users can:

🔐 Register & Login securely

👤 Manage user profiles with profile pictures

✍️ Create, update, and delete blog posts

📚 Browse posts with pagination

🔎 View posts by specific users

📧 Reset passwords via email token authentication

🛡️ Secure forms with validation

🗄️ Manage database with SQLAlchemy ORM


This project is ideal for learning backend architecture, authentication systems, database design, and Flask best practices.


---

🎥 Learning Reference

Corey Schafer Flask Playlist:
https://youtube.com/playlist?list=PL-osiE80TeTsak-c-QsVeg0YYG_0TeyXI


---

🛠️ Tech Stack

Backend:

Python 3

Flask

Flask-WTF

Flask-Login

Flask-Bcrypt

Flask-SQLAlchemy

Flask-Mail

ItsDangerous Token Serializer


Frontend:

HTML5

CSS3

Bootstrap

Jinja2 Templates


Database:

SQLite (Development)

(Can be upgraded to PostgreSQL/MySQL for production)



---

🧠 Core Features

🔐 Authentication System

User Registration

Secure Login/Logout

Password Hashing with Bcrypt

Password Reset via Email Token


👤 User Dashboard

Profile Management

Upload/Update Profile Picture

Account Information Update


✍️ Blog Management

Create Post

Read Post

Update Post

Delete Post


📄 Pagination

Dynamic multi-page post browsing


📧 Email Integration

Password recovery system



---

🏗️ Project Architecture

flaskblog/
│
├── static/
│   ├── profile_pics/
│   └── main.css
│
├── templates/
│   ├── layout.html
│   ├── home.html
│   ├── login.html
│   ├── register.html
│   ├── account.html
│   ├── create_post.html
│   └── post.html
│
├── forms.py
├── models.py
├── routes.py
├── utils.py
└── run.py


---

⚙️ Installation Guide

1️⃣ Clone the Repository

git clone https://github.com/yourusername/flask-blog.git
cd flask-blog

2️⃣ Create Virtual Environment

python -m venv venv

3️⃣ Activate Virtual Environment

Windows:

venv\Scripts\activate

Mac/Linux:

source venv/bin/activate

4️⃣ Install Dependencies

pip install -r requirements.txt

5️⃣ Run Application

python run.py

🌍 Open in Browser:

http://127.0.0.1:5000


---

🗃️ Database Models

User Model:

id

username

email

image_file

password

posts (relationship)


Post Model:

id

title

date_posted

content

user_id



---

🔒 Security Highlights

Password Hashing:

bcrypt.generate_password_hash(password).decode('utf-8')

Token-Based Password Reset:

serializer.dumps(user.email, salt='password-reset')


---

🎨 UI/UX Highlights

Responsive Bootstrap Design

Clean Blog Feed Layout

User Profile Image Handling

Flash Messaging for User Feedback

Form Validation & Error Display



---

📈 Future Enhancements

🌐 Deploy on Render / Railway / Azure

🐘 PostgreSQL Integration

💬 Comment System

❤️ Like/Bookmark Feature

🔍 Search Functionality

🏷️ Categories & Tags

📊 Admin Dashboard

🌙 Dark Mode



---

🚀 Deployment Options

Recommended:

Render

Railway

Heroku (if available)

Microsoft Azure App Services



---

📸 Screenshots

Suggested Sections:

Home Page

Login/Register

User Dashboard

Blog Post Editor


(Add screenshots here once deployed for a premium GitHub look)


---

📚 Key Learnings

This project demonstrates:

Backend:

Flask Routing

MVC Pattern

ORM Integration

Authentication

Token Security

Email Services


Frontend:

Template Inheritance

Bootstrap Components

Dynamic Rendering



---

🤝 Contribution

Contributions, forks, and feature suggestions are welcome.

Fork → Clone → Improve → Pull Request


---

📜 License

This project is for educational and portfolio purposes.


---

👨‍💻 Author

Rajdeep Chakraborty
Full Stack Developer | Python | Flask | JavaScript


---

⭐ Acknowledgement

Special thanks to Corey Schafer for one of the best Flask learning series available on YouTube.


---

🌟 If you found this useful:

⭐ Star the repo

🍴 Fork it

🚀 Build your own upgraded version