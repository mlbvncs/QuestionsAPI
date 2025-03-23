# QuestionsAPI

Back-end project of an API with ENEM questions on mathematics and physics using Python (FastAPI).

## Objectives

Create a back-end project of an API that allows the user to access a limited number of ENEM questions on mathematics (Proportional quantities and probability) and physics (Energy and wave theory).

## Getting Started

### Prerequisites

- *Python*: Install the latest version of Python from [python.org](https://www.python.org/).

### Installation

1. Fork this repository.
   
2. Open the project in your compiler.
   
3. Open the integrated terminal.
   
4. Create your .env file:
   
   ```
   python -m venv .env
   ```
   
5. Activate the virtual environment (if your compiler doesn't do it by itself) :

   ```
   .env/Scripts/activate
   ```
   
6. Install all the libraries needed to run the .py file:

   ```
   pip install -r requirements.txt
   ```

### Running the Code

1. Run the app.py archive:

   ```
   uvicorn app:app
   ```
