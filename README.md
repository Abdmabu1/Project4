Environment Variables
Replace the values in .env.example with your values and rename this file to .env:

FLASK_APP: Entry point of your application; should be wsgi.py.
FLASK_ENV: The environment in which to run your application; either development or production.
SECRET_KEY: Randomly generated string of characters used to encrypt your app's data.
LESS_BIN (optional for static assets): Path to your local LESS installation via which lessc.
ASSETS_DEBUG (optional): Debug asset creation and bundling in development.
LESS_RUN_IN_DEBUG (optional): Debug LESS while in development.
COMPRESSOR_DEBUG (optional): Debug asset compression while in development.
Remember never to commit secrets saved in .env files to Github.