# Flask API Project

 This repository contains a simple Flask API project that responds to a specific endpoint with a "Hello World" message along with the variant number. Additionally, it includes instructions for setting up the development environment.

## Getting Started
 Prerequisites

1. Python (as specified in the project requirements)
2. pip (to install Python packages)
3. git (for version control)

## Installation
1. Clone the repository: https://github.com/philipko287/PP_lab3.git
## Create and activate a virtual environment:
python -m venv venv

mac os:
- source venv/bin/activate

windows:
- myenv\Scripts\activate
## Install the required packages:
- cd PP_LAB3
- pip install -r requirements.txt
## Running the Application
Run the Flask application:
- python FLASK.py 
## Testing the API Endpoint
You can test the API endpoint using the following curl command:
- curl -v -XGET http://127.0.0.1:5000/api/v1/hello-world-1
