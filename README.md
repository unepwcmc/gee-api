# Google Earth Engine API - A Python wrapper

## Setup

* Make sure Python > 3.3 is installed
* Clone this repo and cd into the main folder
* Create a new virtual environment named `gee-api`
  - `python -m venv gee-api`
* Activate the virtual environment
  - `source gee-api/bin/activate` (OS X & Linux)
  - `gee-api\Scripts\activate` (Windows)
* If you want to deactivate your virtual environment:
  - `deactivate`
* Install dependencies
  - `pip install -r requirements.txt`

You can run the application with: `python app.py`.
The recommended way of running the app is: `flask run`. But you might need to configure some environment variables like:

* `export FLASK_ENV=development` (use `set` instead of `export` under Windows)
* `export FLASK_DEBUG=1` (useful to see new changes without restarting the server)

You can then connect to `localhost:5000` and enjoy!
