# Sblog - Flaskr

This is the basic Flaskr blog that you build over in the [tutorial](http://flask.pocoo.org/docs/1.0/tutorial/)

We are reusing this as a coding homework

## Install

**Be sure to use the same version of the code as the version of the docs
you're reading.** 

You probably want the latest tagged version, but the default Git version is the master branch. Get the repository using the following commands in a terminal on Linux, Mac, or Windows:

```
    # clone the repository
    $ git clone git@github.com:gotrecha/sblog.git
    $ cd sblog
```

### Create a virtualenv and activate it
#### On linux or Mac

```
    $ python3 -m venv venv
    $ . venv/bin/activate
```

#### On Windows cmd

```
    $ py -3 -m venv venv
    $ venv\Scripts\activate.bat
```

### Install Flaskr

```
    $ pip install -e .
```

## Run

### On Linux or Mac:

```
    $ export FLASK_APP=sblog
    $ export FLASK_ENV=development
    $ flask init-db
    $ flask run
```

### On Windows:

```
    > set FLASK_APP=sblog
    > set FLASK_ENV=development
    > flask init-db
    > flask run
```

Open http://127.0.0.1:5000 in a browser.


## Test

### On Linux, Mac, or Windows using standard pytest:

```
    $ pip install '.[test]'
    $ pytest
```
### On Linux, Mac, or Windows using coverage utility:

```
    $ coverage run -m pytest
    $ coverage report
    $ coverage html  # open htmlcov/index.html in a browser
```

## Develop
1. Switch to the [Issues](https://github.com/gotrecha/sblog/issues/) page in the github UI
2. Review the [bug report](https://github.com/gotrecha/sblog/issues/1)
3. Create a new branch called initial-startup-error
4. Update your working directory to the new branch
5. Implement a fix for the initial startup error
6. Push the changes to the remote branch
7. Submit a pull request for review of the bug fix implementation
8. Return to [Issues](https://github.com/gotrecha/sblog/issues/) page in the github UI
9. Select two of the enhancements listed and repeat steps 2 thru 7 for the enhancements selected 
