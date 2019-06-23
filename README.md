# Flaskr Tutorial

The source code is based on the [Flaskr Tutorial](http://flask.pocoo.org/docs/1.0/tutorial/) from the flask project.

## Create and setup the Python environment
``` 
python -m venv venv
```

``` 
source ./venv/bin/activate
```

## Install flask and co.
``` 
pip install flask pytest coverage
```

``` 
flask --version
```

## Running the app
``` 
export FLASK_APP=flaskr
export FLASK_ENV=development
flask run
```


## Running the tests

``` 
pytest
```


## Testcoverage

``` 
coverage -m pytest
coverage report
covergae html
```
