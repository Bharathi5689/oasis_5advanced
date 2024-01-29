# ChatApp - Django 

## Description

This Django project implements a simple chat application with user authentication. Users can sign up, log in, and interact with a chatbot. The chatbot provides responses based on predefined patterns in the responses.txt file. The project also supports multimedia file uploads during chat interactions.

## Installation

1. Clone the repository:
   
     git clone https://github.com/your-username/chatapp-django.git

2. Navigate to the project directory:

	cd chatapp-django

3. Create a virtual environment:

	python -m venv venv

4. Activate the virtual environment:

	. On Windows:

		venv\Scripts\activate

	. On Linux/macOS:

		source venv/bin/activate

5. Install the required dependencies:

	pip install -r requirements.txt

6. Apply migrations:

	python manage.py migrate


## Usage

1. Run the development server:

	python manage.py runserver

2. Access the application in your web browser at http://localhost:8000.

## Features

. User Authentication:

	. Signup
	. Login
	. Logout

. Chat Functionality:

 	. Users can input text and receive bot responses
	. Supports multimedia file uploads during chat interactions

. App Pages:

	. Account Profile
	. Chat
	. MyApp Page
	. Main Page

