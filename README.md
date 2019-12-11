## USF MSDS 699: Machine Learning Laboratory
Final Project: Soccer Player Transfer Value Prediction

###### Team Members
* Sunny Kwong ([@kwongsunny7](https://github.com/kwongsunny7))
* Charles Siu ([@chunheisiu](https://github.com/chunheisiu))
* Sean Tey ([@seantey](https://github.com/seantey))
* Andrew Young ([@andrewhowcool](https://github.com/andrewhowcool))

### Data Source
* [FIFA 19 Complete Player Dataset](https://www.kaggle.com/karangadiya/fifa19)

### Research Questions
* Why are some soccer players worth more than others?
* Can we predict the value of a soccer player in the transfer market from their ratings and characteristics?

### Abstract
We fitted a Random Forest model to predict the value of a FIFA 19 player based on his ratings and characteristics in the game. Using the model, we concluded that **reaction time** and **age** are the most important attributes of a player. Meanwhile, attacking player attributes are more predictive than defensive player attributes. Other important attributes include **ball control** and **goalkeeper reflexes**.

### Order of Notebook Execution
1. [Data Cleaning](notebooks/clean.ipynb)
2. [Model Selection and Training](notebooks/final_consolidation.ipynb)

### Data Cleaning
The data cleaning and feature engineering process are recored in the [Clean Notebook](notebooks/clean.ipynb).

### Model Selection and Training
The modeling selection and training process are recorded in the [Final Consolidation Notebook](notebooks/final_consolidation.ipynb).
