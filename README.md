# Python-Flask
Python-Flask API using Flask render and templates while fetching and storing data in MySQL database.

## Modules
pip install Flask
pip install flask-mysql
Ref: https://flask-mysql.readthedocs.io/en/latest/#

pip install Flask-WTF

Set Up
## MySQL Script
CREATE TABLE articles_app.users(id integer AUTO_INCREMENT PRIMARY KEY, name VARCHAR(100), email VARCHAR(100), username VARCHAR(30), password VARCHAR(100), register_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP);
