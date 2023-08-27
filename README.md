# QR-Generator-App

This is a simple web application built using Flask that generates QR codes based on user input. Users can input a URL or text, and the app will generate a QR code image representing that input.

## Prerequisites
Before you can run this Flask app, you need to have the following installed:

Python (version 3.x)
Flask
qrcode
Pillow (PIL)
A web browser

## Installation
1. Clone the Repository: Begin by cloning this repository to your local machine using the following command.

      `git clone https://github.com/Djaberkaci/QR-Generator.git`

2. Navigate to the Project Directory: Move into the project directory.
  
     `cd qr-generator`

3. Install Dependencies: Install the required dependencies using pip. If you have a virtual environment, activate it before running the following command.

      `pip install Flask qrcode Pillow`
## Usage


1. Run the App: Start the Flask development server by executing the following command:
`python app.py`

2. Access the App: Open your web browser and go to http://127.0.0.1:5000/. This will take you to the app's home page.
3. Generate QR Code: On the home page, you can input a URL or text in the provided field. Click the "Generate QR Code" button to create a QR code for the input.
4. View QR Code: The generated QR code image will be displayed on the same page below the input form.

## Contributing
If you find any issues with the app or want to contribute improvements, feel free to fork the repository, make changes, and submit a pull request. We welcome your contributions!
