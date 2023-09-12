# Simple TODO Application

This is a simple TODO reminder application that allows one to create, update and manage their tasks easily.

## Usage

One can add/create a task and it will be listed. They can also filter by a search criteria, whether completed or uncompleted. They can also edit, delete and also mark as completed.

## Technologies Used

- Flask: A micro web framework for python.
- HTML5/CSS3: For styling the website.
- MongoDB: A NoSQL database for storing task data.
- Python: The main programming language used to build the web application.

## Installation

Before running/installing the application, make sure you have the following prerequisites installed:

- Python3.x: You can download from the official website [Python website](https://www.python.org/downloads/).
- MongoDB: You can download from the official website [MongoDB](https://www.mongodb.com/try/download/community).

- Flask: You can follow the steps from this website to install it to your machine [Flask](https://linuxize.com/post/how-to-install-flask-on-ubuntu-20-04/).

- PyMongo: This is a simple but powerful Python distribution containing tools for working with MongoDB and is the recommended way to work with MongoDB from Python. [PyMongo](https://pymongo.readthedocs.io/en/stable/installation.html).

- BSON: Used for getting objectId property of mongodb document. [BSON](https://pypi.org/project/bson/).

Once you have them downloaded, follow the  below steps to install the project:

1) Clone this repository to your local machine

         git@github.com:Musyoki-Wambua/Simple-Python-Web-APP.git

2) Navigate to the project directory:

        cd Simple-Python-Web-APP

3) (Optional)  Create a virtual environment(Recommended):

        python -m venv venv

4) Activate the virtual enviroment:

        source venv/bin/activate

5) Start the Flask application:

        python app.py

Visit [here]( http://localhost:5000 )  or [http://localhost:5000](http://localhost:5000 ) on your web browser to access the TODO application.

## LICENSE

This repository is distributed under the ISC License.

## Author

This repository is maintained by: [Joseph Wambua](https://github.com/Musyoki-Wambua).
