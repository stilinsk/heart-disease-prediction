# END TO END  RANDOM FOREST ALGORITHM
### In the following project we will be implementing a Random Forest Algorithm  and end toe nd model where we will be implementing the random forest regression algorithm and we will be deploying it using flask and fastapi
  We will fisrt be describing all the files that are in this project briefly explaining what each file perfoms and what it contains

  1. Templates - This file contains the frotn end code for the model we will be deploying using using flask we are using html,css  for the development  of the front end interface
  2. Gitignore -This is a file that is provided in github and one can also create it using vscode it is used to store files that you ant to 'ignore'   when committing the file to github there are files that dont need to be commited such as the environment that one will create ,there is  no need to commit all these files as theyy  actually wont be used thus this is where the gitignore comes in handy.
  3. Dockerfile -A  dockerfile is very important when deploying the app as a container for it to be used in teams using collaboration it somes in handy  when  simplyfing set up in diffferent  machines when used b different team members ,thus comes in handy while collaborating   with different team members.
  4. app.py-basically this is the fastapi framework that requires no front end modification to run ( formerly kmown as the swaggerapi
  5. flask.py -it is directly connected to the templates files where when the flask app is run it connects to the templates file and displays the frontend in the templates file
  6. Heart-disease.ipynb -it is a jupyter notebook that contains the ingestion of the data,the cleaning of the data,the building of the model and the fine tuning of our model which brings us to the other bit saving the model
  7. trained-model.sav- this file contains the file and  the model that we have saved and we connect it to the flask.py and to the app.py  where it will make predictions based on the file we have saved
  8. Requirements.txt -The requirements.txt file is used to load all the libraries that we will need for the model to run in the environment that we create in our vscode


## Project Overview
In the following notebook we will be predicting  the likelihood of a person of getting a heart disease based on the following factors
