<h1>Flask Application</h1>

<h2>To start the Flask server:</h2>

    <ul>
    <li>install dependencies (Flask and SQLalchemy NOTE: this project is curretly configured to use SQLite)
    `pip install -r requirements.txt`
    <li>create and migrate the db
    <br>
    `python3`
    <br>
    `from app import db`
    <br>
    `db.create_all()`
    <li>start flask endpoint by running app.py
     `python3 app.py`
    </ul>

<h2>Your application will now be running at [`localhost:5000`](http://localhost:5000) which you can visit with your favorite browser.</h2>