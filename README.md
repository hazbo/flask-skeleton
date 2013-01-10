# Flask Skeleton

This is a small and simple skeleton application using Python's Flask framework. It includes Bootstrap by Twitter.

## Installation
This is up to you, however I used virtualenv to install Flask, like so:

	$ virtualenv src
	$ cd src
	$ sudo pip install Flask

This just stops anything conflicting with the global Python setup. The application is located in the `app` directory.

## Usage
Once you have the code, you can simply run the app using the following:

	$ cd app
	$ python app.py

You can build from this in whatever way you wish, adding a new route is as simple as:

@app.route('contact')
def contact():
	render_template('contact.html')

The above could be used to load a contact page.

## Extra
I will be adding more examples, and making this a lot easier to use in the near future. Still very new to Flask, and still just as new to Python.
