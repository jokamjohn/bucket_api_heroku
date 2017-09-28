# Bucket List API(Heroku deployment)

The api enables you to create/ register a user within the application.

- **Checkout my [Post](https://medium.com/@johnkagga/deploying-a-python-flask-app-to-heroku-41250bda27d0)
on how to deploy this application to Heroku**

- **I wrote up a post on medium of how I developed this
API, you can find it [here](https://medium.com/@johnkagga/how-i-developed-an-api-in-python-using-flask-4e388674f1)**
## Usage

## Starting the application
In order to run the application set the environment
variable below.
```
Windows
set FLASK_APP=run.py

Unix
export FLASK_APP=run.py
```
Then run the command below to start the application.
```
flask run
```

## API Documentation

The api documentation is hosted as the homepage
of the application.


## Running tests
Before running the application tests, update your env variables
```
export  APP_SETTINGS=app.config.TestingConfig
export DATABASE_URL_TEST=<postgres database url>
```

### Running tests without coverage
You can now run the tests from the terminal
```
python manage.py test
```

### Running tests with coverage
You can also run tests with coverage by running this command in the terminal
```
nosetests --with-coverage --cover-package=app
```
