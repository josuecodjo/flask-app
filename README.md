# Flask App with Pytest

## Getting started

To run the project follow these commands:

- Clone the repository
- cd cloned_repository/flask_pytest
- python3 -m venv .venv
- source .venv/bin/activate
- pip install -r requirements.txt
- pytest  #---> to run the test
- coverage run -m pytest --disable-warnings -v
- coverage report
- coverage xml
- flask run --host 0.0.0.0 --port 5400 #----> To launch the application