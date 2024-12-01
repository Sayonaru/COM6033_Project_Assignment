# COM6033_Project_Assignment

## Spotify Song Recommender
The following assignment develops a flask web app which includes a KMeans algorithm to find the shortest distances between the user songs and similar songs in the same cluster. 5 Kaggle provided datasets have been used in both the algorithm and analysis with visualisation. 

I have split them up as I am interested in how the data was being represented and finding trends in the data that could have lead to a different undertaking of the problem. \
Visualising was a key part in breaking down the steps required for the problem by seeing how the variables in the data interacted with each other, especially in the clusters which was used in the main algorithm.

#### Directory
+ All of the class sessions are found in the Sessions folder. Sessions 6 & 7 were having slight problems but worked with the use of Google CoLab to run on the correct version and found the solution, just missing a few steps due to unresolved conflicts.
+ Since the original dataset I wanted to use was too big, the first iteration of the assignment is found in project_assignment.ipynb, then pivotting to a manageable database in project_assignment_pivot.ipynb.
+ Similarly, the first iteration of the web app can be found in ./COM6033_Project_Assignment/Project1 where it attempts a machine-model approach. ./COM6033_Project_Assignment/Project2 is the working KMeans approach which was done due to the errors and time constraints of the machine-model approach.

## Running
#### Installing necessary files
Start by creating a virtual environment. This can be done by entering the following command into powershell:
```
python -m venv venv
```
After creating it, you'll need to activate it by entering the following command:
```
venv/Scripts/Activate.ps1
```

Once the virtual environment is running, the necessary dependancies should be available to download by running:
```
pip install -r requirements.txt
```
#### Running decided project
If you would like to run the first project, you will need to navigate the file that contains "app.py" which should be done by entering:
```
cd COM6033_Project_Assignment/{Replace with which project you want (Either Project1/Project2)}
```
Then run the flask app by entering:
```
python app.py
```
This will create the app in the browser by visiting http://127.0.0.1:5000/

