# Coffee and Wifi Website Portfolio Project 7 Day 88 100 Days of Python Course
This Project is a Simple Python Web Development Project, a Database of Coffee Shops and How Remote Work Friendly they are.
#
This is a Flask web application that allows users to submit, view, and manage a list of cafes along with key information such as location, coffee rating, WiFi availability, and power socket access. The 
rm handling and validation, Bootstrap 5 for styling, and stores data in a CSV file.

application uses Flask-WTF for fo![Screenshot 2025-06-16 145109](https://github.com/user-attachments/assets/62857308-11a3-4079-a334-3e70d41cf8a9)

https://github.com/user-attachments/assets/aa9256a8-93c0-4828-a83d-aa8a29362529

#

Features:

Add a new cafe by filling out a form:

![Screenshot 2025-06-16 145146](https://github.com/user-attachments/assets/231dc877-b99d-400d-94e1-5ab6efcb0d22)
![Screenshot 2025-06-16 145224](https://github.com/user-attachments/assets/ff6ffe98-38ab-4279-8be8-6abdc2de6793)
https://github.com/user-attachments/assets/d6193f37-c7bf-4c2c-8a42-3849b4404e14

View a list of all submitted cafes in a table format:

![Screenshot 2025-06-16 145124](https://github.com/user-attachments/assets/e0cd29ee-306a-4832-b423-2b3dec4010fd)

Record amenities such as WiFi and power sockets:

![Screenshot 2025-06-16 161107](https://github.com/user-attachments/assets/3116dd45-1fbc-40af-bc9e-366c4ede8ce7)
![Screenshot 2025-06-16 161131](https://github.com/user-attachments/assets/f3ae1348-c692-451c-bc37-0e09aae46403)

Rate Coffee Shop on a scale from 1 to 5:

![Screenshot 2025-06-16 161054](https://github.com/user-attachments/assets/38e9a811-e41e-4a8e-a119-3d135a11622a)


Delete cafes by name:

https://github.com/user-attachments/assets/9aab48eb-715c-4b18-a853-2a99ce2a5e1e

Store and retrieve data from a simple CSV file

#

Technologies Used:

Backend: Python with Flask

Frontend: HTML and Bootstrap 5

Forms and Validation: Flask-WTF and WTForms

Data Storage: CSV file

#

The main files and directories included are:

templates/
index.html
add.html
cafes.html

cafe-data.csv
app.py
README.md

#

Application Flow:

The home page is a static landing page.

The add cafe page presents a form where users can submit new cafe entries including the name, location (Google Maps URL), image URL, website URL, opening and closing times, and ratings for coffee, WiFi, and power sockets.

Submitted data is appended to a CSV file.

The cafes page reads from the CSV file and displays all entries in a tabular format.

Cafes can be deleted based on their name using the delete route.

#

Form Fields:

Cafe name

Image URL

Website URL

Location on Google Maps

Opening time

Closing time

Coffee rating (options from one to five cups)

WiFi availability (yes or no)

Power socket availability (yes or no)

#

Running the App: (My image and csv files are not included, so running instructions are hypothetical)

Clone the repository to your local machine

Install the required Python libraries (Flask, Flask-WTF, Flask-Bootstrap)

Run the app.py file

Open a web browser and go to http://127.0.0.1:5000/ to use the app

#

Possible Future Enhancements:

Use a database such as SQLite or PostgreSQL instead of CSV

Add authentication for cafe submissions and deletions

Preview images based on the provided URL

Add search and filter options for cafes
