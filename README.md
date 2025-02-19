# Usage Guide
This Project requires the following tools:
- Python 3.6 or higher
- MySQL 80

## Getting Started
### Step 1: Install the dependencies listed in `requirements.txt`
```
$ pip install -r requirements.txt
```
### Step 2: Make Sure that you have a MySQL Server up and running either in your local computer or hosted remotely

### Step 3. Configure the database for the app to use
- Open the `mysql.cfg` file with any text editor to edit your MySQL user and password in the respective fields for the app to connect to it.<br/>
*(You can also edit host and port number if the MySQL Server is hosted remotely)*<br/>
Also, you can change the MySQL database name for the app to use.

### Step 4: Run
Run the webapp by running either &nbsp; `flask run` &nbsp; **OR** &nbsp; `python app.py` &nbsp; command<br/>
By default, a flask application runs on port `5000` on `localhost`. So head over to http://localhost:5000 and start using!