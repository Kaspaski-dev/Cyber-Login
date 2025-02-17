# Cyber-Login
Cybersecurity Web Application: This is a web application project built with Flask, focused on the theme of cybersecurity. The application allows users to register, log in, and manage accounts with logical deletion functionality. Administrators can manage users (delete and restore) using a logical deletion system in the database. 

# Cybersecurity Web Application

This is a **cybersecurity web application** built with **Flask** that allows user registration, login, and account management with a **logical deletion** approach. The application features a **futuristic** and **cyberpunk** design with dynamic animations and vibrant colors like **neon blue** and **magenta** to simulate a high-tech and secure environment.

## Features

- **User Registration**: Users can register with a password that must meet security requirements (at least 8 characters, one uppercase letter, and one number).
- **Login**: Users can log in to the system with their credentials.
- **Logical Deletion**: Administrators can logically delete users (without physically removing them from the database) and restore them if needed.
- **Admin Interface**: Administrators can manage users through an admin interface where they can delete or restore logically deleted users.
- **Cybersecurity Design**: The design follows a **cybersecurity** theme, using **glitch effects**, **glow animations**, and **dynamic backgrounds** that represent a cutting-edge, tech-focused environment.

## Technologies Used

- **Flask**: Python web framework for building the application.
- **SQLite**: Lightweight database for storing users and data.
- **CSS**: Custom styles with a **cyberpunk** theme, using animations and bright colors like **neon blue**.
- **HTML and Bootstrap**: Basic structure and visual components.

## Requirements

To run this project on your local machine, you need to have:

- **Python 3.x**
- **Flask**
- **SQLite3**

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/cybersecurity-project.git
   cd cybersecurity-project
2.Create a virtual environment (optional, but recommended):
Copy
python3 -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

3.Install the required dependencies:

Copy
pip install -r requirements.txt

4.Run the Flask development server:

Copy
python app.py

5.Open your browser and visit http://127.0.0.1:5000/ to access the app.

Usage
Users can register with a username and a password that meets security requirements.
After registration, users can log in with their credentials.
Administrators can access the admin interface where they can logically delete and restore users.
