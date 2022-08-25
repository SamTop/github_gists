# Retrieve github user gists

- Project setup
  - Clone the project
  - Install dependencies:
    - `cd github` 
    - `pip install -r requirements.txt`
  - Configure `.env` file
  - Run migrations:
    - `alembic revision -m "First commit"` 
    - `alembic upgrade head`
  - Run server: `uvicorn main:app`
