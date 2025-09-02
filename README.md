# ACE Fitness And Gym Management System

## Setup and Run Locally

1. Clone the repo  
2. Create a virtual environment and activate it  
3. Install dependencies: `pip install -r requirements.txt`  
4. Run the app: `python app.py`  
5. Access the app at `http://localhost:5001`

## Running Tests

- Run tests locally with:  
  `pytest`  
- Or run tests inside Docker:  
  `docker build -t my-python-app .`  
  `docker run --rm my-python-app pytest`

## GitHub Actions Pipeline

- Automatically triggers on every push to `main`.  
- Builds the Docker image.  
- Runs Pytest unit tests inside the Docker container.  
- Check pipeline results under the ‘Actions’ tab in GitHub.
