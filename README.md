<h1>Flask Application</h1>

<h2>To start the Flask server:</h2>

<ul>
    <li>install dependencies (Flask and SQLalchemy NOTE: this project is curretly configured to use SQLite)
    <br>
    <code>pip install -r requirements.txt</code>
    <li>create and migrate the db
    <br>
    <code>python3</code>
    <br>
    <code>from app import db</code>
    <br>
    <code>db.create_all()</code>
    <li>start flask endpoint by running app.py
    <br>
     <code>python3 app.py</code>
</ul>

<h3>Your application will now be running at <a href='http://localhost:5000'>localhost:5000</a> which you can visit with your favorite browser.</h3>