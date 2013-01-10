# Flask Skeleton

This is a small and simple skeleton application using Python's Flask framework. It includes Bootstrap by Twitter.

## Installation
I use virtualenv to install Flask, so you could do the following. (This will instruct you how to install Python/Pip if you havn't already done so)

### Ubuntu

	$ sudo apt-get install python-pip python-dev build-essential
	$ sudo pip install --upgrade pip
	$ sudo pip install --upgrade virtualenv
	$ cd /path/to/your/workspace
	$ git clone https://github.com/harry-lawrence/flask-skeleton.git src
	$ virtualenv src
	$ cd src
	$ . bin/activate
	$ sudo pip install Flask
	$ cd src/app
	$ python app.py

### OS X

To install Pip, you can either use:

	$ wget http://pypi.python.org/packages/source/p/pip/pip-0.7.2.tar.gz
	$ tar xzf pip-0.7.2.tar.gz
	$ cd pip-0.7.2
	$ python setup.py install

Or:

	$ sudo easy_install pip

As for the rest:

	$ sudo pip install virtualenv
	$ cd /path/to/your/workspace
	$ git clone https://github.com/harry-lawrence/flask-skeleton.git src
	$ virtualenv src
	$ cd src
	$ . bin/activate
	$ sudo pip install Flask
	$ cd src/app
	$ python app.py

### Windows

Sorry it's been too long since I last used Windows. Not too sure what it would entail. If you know and would like to help, be sure to make a pull request!

The above will install everything you need, get you setup with Python/Pip/Virtualenv/Flask and the sample skeleton application.

## Extra
I will be adding more examples, and making this a lot easier to use in the near future. Still very new to Flask, and still just as new to Python.
