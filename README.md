# Movie Analysis Project
**Authors:** Branden Rew & Cooper McCombs

## Repository Contents
- [Data](https://github.com/CoopaM/Star-Project/tree/main/Data)
- [Notebooks](https://github.com/CoopaM/Star-Project/tree/main/Notebooks)
- [gitignore](https://github.com/CoopaM/Star-Project/blob/main/.gitignore)
- [FinalNotebook.ipynb](https://github.com/CoopaM/Star-Project/blob/main/FinalNotebook.ipynb)
- [README.md](https://github.com/CoopaM/Star-Project/blob/main/README.md)
- [The Stars Presentation](https://github.com/CoopaM/Star-Project/blob/main/The%20Stars.pdf)
## Table of Contents
- [Overview](#overview)
- [Business Problem](#business-problem)
- [Data](#data)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [For More Information](#for-more-information)
## Overview
Throughout this project we use the data we gathered to develope a model that will allow us to make a prediction. At the end we will give a summary on what our stake holder should do with this information.

## Business Problem
Elon Musk has hired us to predict if a star is variable or not so he can do more research on the star and its surrounding. If a star is variable it tells us that there may be objects (such as planets) in its orbit. For this reason, we are looking for stars that have high variability.

## Data
This data was gathered from one of the European space agency's satellites also known as Hipparcos with over 70k entries (post cleaning). Whenever we ran into null values, we filled the nulls of the numerical columns with the median of that column and 
filled the nulls in the categorical columns with 'none'.

## Results
We chose to use a tree model because we believe there is interaction between the features and this model will automatically take care of that for us. We ran a grid search to try to get the best parameters to see what would make our model the best it could be.
![]()
This graph represents a confusionn matrix that shows all of our type 1 and type 2 error probabilities.

## Conclusion
We know our model is not perfect, but we do suggest for Mr.Musk to use our model to predict whether a star is variable or not.
## Future Work
In the future, we are planning on:
- Creating more Models
- Exploring the different levels of variability
- Developing more knowledge on the subject gaining more domain expertise
## For More Information
- [Slide Presentation](https://github.com/CoopaM/Star-Project/blob/main/The%20Stars.pdf)
- [Dataset](https://www.kaggle.com/datasets/konivat/hipparcos-star-catalog)
 
## Repo Map
```
├── Data                                    
|   ├── hipparcos-voidmain.csv  
|   ├── HoldoutData.csv  
|   └── UsableData.csv
├── Notebooks  
|   └── Draft Notebook.ipynb
├── .gitignore 
├── FinalNotebook.ipynb 
├── README.md 
└── The Stars.pdf
```