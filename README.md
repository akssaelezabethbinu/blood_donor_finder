# Blood Donor Finder

A simple web application for registering and searching blood donors.
<img width="1892" height="921" alt="Screenshot 2026-09-29 212623" src="https://github.com/user-attachments/assets/af1e8ea0-60dd-4bf1-919a-1ca5b26a4556" />
<img width="1890" height="843" alt="Screenshot 2026-09-29 212548" src="https://github.com/user-attachments/assets/96742e26-b2d4-470e-987b-9ea0fee86c7d" />
<img width="1897" height="960" alt="Screenshot 2026-09-29 212535" src="https://github.com/user-attachments/assets/7a1c89d0-e483-47d0-955b-b7e38480bea8" />

## About the Project

Blood Donor Finder is a web application developed using Python Flask and SQLite.

The main purpose of this project is to make it easier to store donor details and search for suitable blood donors when needed.

## Features

- Donor registration
- Search donors
- Blood group compatibility checking
- Emergency blood request<img width="1901" height="967" alt="Screenshot 2026-09-29 212509" src="https://github.com/user-attachments/assets/232ab552-5d16-446d-985d-49f018df9fe9" />
<img width="1901" height="967" alt="Screenshot 2026-09-29 212509" src="https://github.com/user-attachments/assets/4bcc3a5c-1e10-463b-9764-8491fc2b28b2" />

- Excel file upload for donor details
- View emergency requests

## Technologies Used

- Python
- Flask
- SQLite
- HTML
- CSS
- Bootstrap
- OpenPyXL

## How the Project Works

1. Donor registers by entering their details.
2. Donor information is stored in the database.
3. Users can search for donors based on blood group.
4. Blood group compatibility can be checked.
5. Users can submit an emergency blood request.
6. Admin can manage donor and request information.

## Project Structure

blood_donor_finder/
│
├── app.py
├── templates/
├── static/
├── .gitignore
└── README.md

## How to Run

### Clone the repository

git clone https://github.com/akssaelezabethbinu/blood_donor_finder.git

### Open the project folder

cd blood_donor_finder

### Create a virtual environment

python -m venv venv

### Activate the virtual environment

For Windows:

venv\Scripts\activate

### Install the required packages

pip install flask openpyxl

### Run the application

python app.py

Then open the following address in your browser:

http://127.0.0.1:5000/

## Future Improvements

- Donor availability status
- Distance-based donor search
- Emergency donor priority
- Email or SMS notifications
- Better mobile interface
- Online deployment

## Developer

**Akssa Elezabeth Binu**

B.Tech Computer Science and Engineering
