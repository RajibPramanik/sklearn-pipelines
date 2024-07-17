<h1>Titanic Prediction Pipeline</h1>


<h3>Contents</h3>

- `pipe.pkl:` Serialized machine learning model pipeline.

- `predict-pipeline.ipynb:` Jupyter notebook for making predictions using the trained model pipeline.

- `titanic-pipeline.ipynb:` Jupyter notebook for training the machine learning model pipeline.

- `train.csv:` Dataset used for training the model, containing information about Titanic passengers.



<h2>Usage</h2>
<h3>Training the Model</h3>

- Open the titanic-pipeline.ipynb notebook.

- Run the cells to train the model pipeline.

- The trained model pipeline will be saved as pipe.pkl.

<h3>Making Predictions</h3>

- Open the predict-pipeline.ipynb notebook.

- Load the pipe.pkl file.
- Use the loaded model pipeline to make predictions on new data.

<h3>Dataset</h3>

The train.csv file contains the Titanic dataset with the following columns:

- PassengerId: Unique identifier for each passenger

- Survived: Survival indicator (0 = No, 1 = Yes)

- Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

- Name: Passenger's name

- Sex: Passenger's sex

- Age: Passenger's age

- SibSp: Number of siblings/spouses aboard the Titanic

- Parch: Number of parents/children aboard the Titanic

- Ticket: Ticket number

- Fare: Fare paid by the passenger

- Cabin: Cabin number

- Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
