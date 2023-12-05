# Buy A Stick
A simple E-commerce website using Flask.
  
## Dependencies ##
1. Python3
2. Flask
3. Sqlite

## How to run ##
1. Set up database by running database.py (Or you can reuse existing database included in the repo)
2. Run main.py
3. Enter localhost:5000 in the browser

## Pipenv instructions ##
1. Install pipenv (python3 -m pip install --user pipenv)
2. Install dependencies (pipenv install --dev)
3. Setup database (pipenv run python database.py)
4. Run the server (pipenv run python main.py)
5. Enter localhost:5000 in the browser

## Useful commands ##
1. python -m pipenv install --dev
2. python -m pipenv run --python 3.11 database.py
3. python -m pipenv run --python 3.11 main.py
4. python -m flask --app main.py run --debug

## Sample User ##
Sample credentials present in existing database:
Username - sample@example.com
Password - sample
