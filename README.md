# spotify_app

### Startup Instructions

1) Clone the repository and change directories to the outer project folder:

`git clone git@github.com:bloominstituteoftechnology/DS_code_along_11.2_deploying_ML_models_starter.git`

`cd DS_code_along_11.2_deploying_ML_models_starter`

2) Ensure that all dependencies are properly installed:

 `pipenv install`

3) Activate the virtual enviroment with:

`pipenv shell`

4) Start up the Flask app.

`flask run`

5) Contrary to best practices, this solution app **does** include a `.env` file with active API Keys. This is to make it easier for the instructor to show the learners a working version of the app. Learners will need to create their own `.env` file and obtain [API keys from Spotify.](https://developer.spotify.com/dashboard/login)  

6) Visit the `/reset` route to generate the `db.sqlite3` file.

[127.0.0.1:5000/reset](http://127.0.0.1:5000/reset)
