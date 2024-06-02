To run the app local:

python3 -m venv venv
. venv/bin/activate
pip install Flask Flask-SQLAlchemy
export FLASK_APP=app.py
export FLASK_ENV=development
flask run


(venv) (base) jalalmujawar@Jalals-Air FLASK-APP % flask run
 * Serving Flask app 'app.py'
 * Debug mode: off
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on http://127.0.0.1:5000
Press CTRL+C to quit
