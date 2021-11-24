web: gunicorn main:app
init: FLASK_APP=main.py python -m flask db init
migrate: FLASK_APP=main.py python -m flask db migrate
upgrade: FLASK_APP=main.py python -m flask db upgrade
