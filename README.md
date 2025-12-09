Blog web application built with Flask Python web framework. 
It supports user registration, login, creating, editing, and viewing blog posts.

Installation and Setup:
1.	Clone the repository:  git clone cd blog_app 
2.	Create and activate a virtual environment:
python -m venv venv # Windows venv\Scripts\activate # macOS/Linux source venv/bin/activate 
3.	Install dependencies: pip install flask flask_sqlalchemy flask_login flask_wtf
4.	Run the application:  python app.py 
5.	Open your browser and navigate to: http://127.0.0.1:5000/ 
6.  Use the test user to login via the browser - username: testuser / password: testpassword - submit the form to login

Technologies:
•	Python 3.x
•	Flask
•	Flask-SQLAlchemy (ORM for SQLite database)
•	Flask-Login (user session management)
•	Flask-WTF (form handling and validation)
•	Werkzeug (password hashing)
•	Jinja2 (templating engine)
•	SQLite (database)

Notes:
•	The database file users.db is created automatically on first run.
•	Passwords are securely hashed using Werkzeug.
•	The app uses Flask-Login to manage user sessions.
•	To reset the database, delete users.db and restart the app.



