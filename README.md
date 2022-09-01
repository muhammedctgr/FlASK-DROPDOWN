# FLASK-DROPDOWN

## OVERVIEW

The idea was to implement a reading of the database tables that have the car brands and models. This information is converted into a python dictionary to feed the two drop down boxes. When selecting the car make, the application displays in the second drop down box the car models that correspond to the car make in ``` @app.route('/_update_dropdown') ```

### Tools
 * Python (Flask)
 * Flask-SQLAlchemy
 * Postgres

## Development Setup
1. **Download the project code locally**

* git clone https://github.com/muhammedctgr/FLASK-DROPDOWN.git
* cd FLASK-DROPDOWN 
* code .
* create a database named dropdown or any name of your choice in postgresql and create tables carbrands and carmodels and populate it
* look in the requirements.txt on how to do this.
* configure your db uri in app.py


5. **Run the development server:**

* export FLASK_APP=myapp
* export FLASK_ENV=development # enables debug mode
* python3 app.py


6. **Verify on the Browser**<br>
Navigate to project homepage [http://127.0.0.1:5000/](http://127.0.0.1:5000/) or [http://localhost:5000](http://localhost:5000) 
