House Pricing Prediction Model
This project contains a machine learning model that predicts the prices of houses based on several features of the houses. The project is implemented in Python using popular machine learning libraries like Scikit-Learn, Pandas, and NumPy.

Files
The following files are included in this project:

templates: This directory contains the HTML templates used for the web app.
.gitignore: This file contains a list of files and directories that should be ignored by Git.
House_Pricing_Prediction.ipynb: This Jupyter notebook contains the code used to train and evaluate the machine learning model.
LICENSE: This file contains the license under which this project is released.
Procfile: This file contains the command to run the web app on a Heroku server.
README.md: This file contains the documentation for the project.
app.py: This Python file contains the code to run the Flask web app.
regmodel.pkl: This file contains the serialized machine learning model that was trained in the House_Pricing_Prediction.ipynb notebook.
requirements.txt: This file contains a list of Python packages required to run the project.
scaling.pkl: This file contains the serialized scaling object that was used to scale the input features in the House_Pricing_Prediction.ipynb notebook.
Usage
To run the web app locally, follow these steps:

Install the required Python packages using pip install -r requirements.txt.
Run the Flask web app by executing python app.py.
Navigate to http://localhost:5000 in a web browser to use the app.
To deploy the web app on a Heroku server, follow these steps:

Create a new Heroku app using the Heroku CLI or the Heroku web dashboard.
Set the FLASK_APP environment variable to app.py using the Heroku CLI or the Heroku web dashboard.
Push the code to the Heroku app's Git repository.
Scale up the web dyno using the Heroku CLI or the Heroku web dashboard.
