# Internship_Flask_TASK_4_URL-Shortener-Web-Application-Basic-
# URL Shortener Web Application (Flask)

##  Project Overview
This project is a full-stack web application built using Flask that allows users to shorten long URLs into compact, shareable links. The application validates user input, generates unique short URLs, stores them in a database, and provides a history dashboard for reviewing previously shortened links.

The project demonstrates backend development, database integration using ORM, frontend rendering, and real-world web application workflow.

---

##  Features
- ✔️ Shortens long URLs into unique short links
- ✔️ Validates URLs before processing
- ✔️ Redirects short URLs to original destinations
- ✔️ Stores URL history in SQLite database
- ✔️ Displays all previous URLs in a history page
- ✔️ Copy-to-clipboard functionality
- ✔️ Responsive UI using Bootstrap
- ✔️ Database persistence using SQLAlchemy ORM

---

## Technologies Used
- Python  
- Flask  
- Flask-SQLAlchemy  
- SQLite  
- HTML  
- Bootstrap  
- JavaScript  

---

## Project Structure
url_shortener/
│
├── app.py
├── instance/
│ └── urls.db
│
├── templates/
│ ├── home.html
│ └── history.html
│
└── static/

yaml
Copy code

---

##  How to Run the Project

### Step 1 – Install Dependencies
pip install flask flask_sqlalchemy validators

yaml
Copy code

---

### Step 2 – Navigate to Project Folder
cd url_shortener

yaml
Copy code

---

### Step 3 – Run the Application
python app.py

yaml
Copy code

---

### Step 4 – Open in Browser
http://127.0.0.1:5003/

yaml
Copy code

---

##  Application Routes
| Route | Description |
|--------|-------------|
| `/` | Home page for entering URLs |
| `/<short_code>` | Redirects to original URL |
| `/history` | Displays all stored URLs |

---

##  How It Works
1. User enters a URL on the home page.
2. Application validates the URL.
3. A unique short code is generated.
4. URL is stored in the database.
5. Short URL is displayed and can be copied.
6. Visiting the short URL redirects to the original URL.
7. History page displays all saved URLs.

---

##  Learning Outcomes
- Flask routing and template rendering
- Database integration using SQLAlchemy ORM
- URL validation and data handling
- Full-stack application workflow
- Debugging and project structuring
- Building reusable backend logic

---

# Author
**Bathula Venu Gopal**  
Data Science Intern – Innomatics Research Labs  
