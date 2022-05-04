#Flask Application

To start the Flask server:

    *install dependencies (Flask and SQLalchemy NOTE: this project is curretly configured to use SQLite)
    `pip install -r requirements.txt`
    *create and migrate the db
    <br>
    `python3`
    <br>
    `from app import db`
    <br>
    `db.create_all()`
    *start flask endpoint by running app.py
     `python3 app.py`


Your application will now be running at [`localhost:5000`](http://localhost:5000) which you can visit with your favorite browser.