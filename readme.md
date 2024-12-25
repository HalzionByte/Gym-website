>>>>>Project Overview

This project is a Flask-based web application designed with multiple pages including a homepage, about page, and membership page. The application uses templates for rendering HTML and static files for styling.

>>>>>Folder Structure
project-folder/
|-- app.py
|-- templates/
|   |-- index.html
|   |-- about.html
|   |-- membership.html
|-- static/
|   |-- styles.css

>>>>>Explanation of Key Files:

app.py:
The main Flask application file.

Routes defined:
/: Homepage.
/home: Alias for homepage.
/about: About page.
/membership: Membership page.

>>>>>templates/

Contains HTML files for each page.

index.html for the homepage.
about.html for about us page.
membership.html for membership page.

>>>>>static/

Stores static files like CSS and images.

styles.css for homepage.
About.css for aboutus page.
membership.css for membership page.

>>>>>Features

Routing: Navigation between multiple pages using Flask routes.

HTML Structure: Each page is built with semantic HTML5.

Styling: Custom CSS for enhancing the UI.

>>>>>How to Run the Application

Install Flask:

pip install flask

Run the Application:

python app.py

Access in Browser:
Navigate to http://127.0.0.1:5000 to view the application.

>>>>>Purpose

An easy too navigate gym registration/information website template.
