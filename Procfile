web: gunicorn main:app
init: FLASK_APP=main.py python3 -m flask db init
migrate: FLASK_APP=main.py python3 -m flask db migrate
upgrade: FLASK_APP=main.py python3 -m flask db upgrade
