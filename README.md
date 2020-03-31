# Website-to-detect-Corona-VirusUpload a picture of the chest X ray, and it tells you whether the person has been infected with the Corona Virus or not.

The website can be accessed at https://coronovirus-prediction.herokuapp.com/

The data set and model used has been taken from https://www.pyimagesearch.com/2020/03/16/detecting-covid-19-in-x-ray-images-with-keras-tensorflow-and-deep-learning/

First run pip install -r requirements.txt

Then run the flask application by python app.py and then go to your browser and type localhost:5000

This application isn't to be used for professional purposes as the model was trained on very less amount of data. Its simply an image classification web app, and it can be used for any model which you have by making the necessary changes.

Other resources used were https://www.datascienceauthority.com/post/deploying-the-machine-learning-model-using-keras-and-flask and the deep learning series by DeepLizard on Youtube - https://www.youtube.com/watch?v=SI1hVGvbbZ4&list=PLZbbT5o_s2xrwRnXk_yCPtnqqo4_u2YGL&index=22

Ignore the Procfile, that was used to deploy the web app on heroku.
