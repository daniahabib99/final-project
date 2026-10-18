# final-project
Titanic Survival Project

Question: How were passenger, class, sex, and age associated with survival on the Titanic?

Data source: It was downloaded from this public GitHub repository https://github.com/RohanAwate/Titanic-Dataset/blob/main/titanic_train.csv The file used is titanic_train.csv, it has 850 rows and 15 columns of passenger information. 

Variables:
  - survived: Categorical/binary, 0 = false, 1 = true
  - pclass: Categorical, 1 = first class, 2 = second class, 3 = third class
  - sex: Categorical, male or female
  - age: Numerical, passenger'a age in years, note that 174 of these values are missing
  - passenger_id: Numerical, id number
  - name: Categorical, passenger's name
  - sibsp: Numerical, number of siblings/spouses aboard
  - ticket: Categorical/text, ticket identifier
  - fare: Numerical, price of ticket
  - parch: Numerical, Number of parents or children aboard
  - cabin: Categorical/text, cabin identifier, some missing values
  - embarked: Categorical, port of embarkation
  - boat: Categorical/text, lifeboat identifier, some values missing
  - body: numerical, body identification number, when recorded, some values missing
  - home.dest: Categorical/text, listed home/destination
  
Project Variables: my analysis will follow survived, pclass, sex, and age in order to explore how passenger characteristics were associated with survival.
  
  
  
My Planned Analysis:
My project will compare the passengers' survival proportions based on sex and class, examine age distributions by survival satus, and it will use graphs and summary statistics to explore patterns within these proportions. The data are obeservational, so the analysis will describe associations.