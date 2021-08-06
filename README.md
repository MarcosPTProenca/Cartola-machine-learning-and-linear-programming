# Cartola machine learning and linear programming
 Using machine learning to predict the score of the soccer players of Campeonato Brasileiro de Futebol and decide the best squad with linear programming

> ## About The Project

This is a project to try to build the best team in Cartola FC. To do that, I did first a regression of the score of the soccer players, second I predicted the winner teams and losers of each round using classification with the program that I made in the repository Machine-learning-soccer-classification to prevend the linear model to choose players from teams that are playing against each other which is bad most of the time and for last I used linear programming to decid the best squad maximizing the score predictions multiplied by some weights like, if the team is playing home or outside, if the teams are playing a classic and the position of the team in the Brasileirão table.


> ## Data

I used the data from the repository caRtola: https://github.com/henriquepgomide/caRtola

> ## Built With

Python in Jupyter Notebook

I decided to try different machine learning approaches to compare the results, so i used XGBoost, Extra Trees, Random Forest and MLP.

> ## Features and scores

![image](https://user-images.githubusercontent.com/88220952/128446921-59617769-083b-4d15-9463-44c4933ca215.png)

The meaning of each feature and its weight can be found in the site: https://www.cartolafcbrasil.com.br/scouts

> ## Data for training and testing

train = 70% of data and test = 30%

> ## The weight of playing home

![image](https://user-images.githubusercontent.com/88220952/128444673-555d8b3a-d7ad-4c78-b4a9-52527ff2f742.png)

The graph show us that playing home is very important for the Campeonato Brasileiro, because the teams win more often home than outside and that's why i added a weight of playing home in the linear programming part.

> ## Results

![image](https://user-images.githubusercontent.com/88220952/128448325-0a33ac64-3223-406d-9516-db442058a77c.png)

Using data from round 14 of 2021, the classification predictions are:

![image](https://user-images.githubusercontent.com/88220952/128448506-fda2bde7-ece9-41f1-97f4-0044f1528857.png)

Using 108 cartoletas, the best squad chosen was:

![image](https://user-images.githubusercontent.com/88220952/128448626-74e855e4-7fa2-4788-9d7d-f5bf46350bd5.png)

Total price = 107.84

Pontuation prediction = 104.13

