# Flask Task 1 - API with JSON File

This is a simple Flask project that returns a JSON list from a local file using an API route `/api`.

## Technologies Used

- Python
- Flask
- JSON
- Git/GitHub

## Folder Structure
flask_assignment/---> Task1/---> app.py -----># Flask application -----> data.txt # JSON data file


## How It Works

When you run the app and visit the route `/api`, it:
1. Reads `data.txt`
2. Converts it to JSON
3. Returns it to the user

## How to Run the App

```bash
# Step into the project folder
cd flask_assignment/Task1

# (Optional) Create a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install Flask
pip install flask

# Run the app
python app.py

#open the browser and go to 
http://localhost:5000/api

#you will get the content in the 'JSON' Format
like this [
  {"name": "Praful", "age": 23},
  {"name": "Alice", "age": 25},
  {"name": "Bob", "age": 22}
]

##Features
-API returns data from a file
-Easy to modify and extend
-Good starting point for learning Flask + JSON

#Author 
Praful Bijalpure

