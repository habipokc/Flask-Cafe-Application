# Flask-Cafe-Application
This is a simple Flask application that allows users to submit information about cafes and stores the data in a CSV file. It also displays the stored cafe data in a user-friendly format.

Prerequisites
To run this application, you need to have the following installed:

-Python (version 3.7 or higher)
-Flask
-Flask-Bootstrap
-Flask-WTF

Installation
Clone this repository to your local machine or download the ZIP file and extract it.
Open a terminal or command prompt and navigate to the project directory.
Create a virtual environment (optional but recommended).
Install the required dependencies by running the following command:

pip install -r requirements.txt

Usage
In the project directory, run the following command to start the Flask development server:

python app.py

Open your web browser and go to http://localhost:5000 to access the application.


How It Works
-The main page displays a list of cafes that have been submitted.
-To add a new cafe, click on the "Add a Cafe" link.
-Fill in the required information in the form, including the cafe name, location (Google Maps URL), opening time, closing time, coffee rating, wifi strength  rating, and power socket availability.
-Click the "Submit" button to add the cafe to the CSV file.
-The new cafe will be displayed on the main page along with the existing cafes.
-You can click on the cafe names to view more details about each cafe.

File Structure
-app.py: The main Flask application file that handles routing and form submission.
-templates/: Directory containing HTML templates used by Flask to render web pages.
-index.html: The template for the main page that displays the list of cafes.
-add.html: The template for the form page where users can add a new cafe.
-cafes.html: The template for displaying the details of each cafe.
-cafe-data.csv: The CSV file that stores the submitted cafe data.

Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
