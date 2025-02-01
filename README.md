This project is a simple API built using FastAPI that calculates the factorial of a given number
The API exposes a single endpoint, /factorial/{starting_number} which takes an integer as input and returns the factorial of that number

GET /factorial/{starting_number}
Returns the factorial of starting_number

Install dependencies: pip install -r requirements.txt
Run the server: uvicorn lab1:app --reload
Test the API via: http://127.0.0.1:8000/docs

Technologies Used:
FastAPI
Uvicorn
Pydantic
Python-dotenv
