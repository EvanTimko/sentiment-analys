# sentiment-analysis

## Objective

- to be able to predict one’s sentiment based on one's sentence or statement

<img width="337" alt="image" src="https://user-images.githubusercontent.com/56888440/227103247-260db027-32f4-4d02-95d6-e3c6b968c5e1.png">

## Data Proccessing

- Retrieve data from internet and by web scrapping
- Clean the data
- Look for empty cells in the data and duplicate and remove them

<img width="850" alt="image" src="https://user-images.githubusercontent.com/56888440/227103766-37f59b9c-861b-4bba-831f-e5dfbeaf4486.png">


## INTERPRETING SENTIMENT

- Setting up our labels creating all possible outcomes
- Then all the feature the clean_content which is used to train the model
- From which predicting one's sentiment is possible
<img width="193" alt="image" src="https://user-images.githubusercontent.com/56888440/227103824-44ccbf97-8e10-4679-a9a4-6374d3d99d06.png">

## CREATING PREDICTION DATA

- train_test_split() performs the split and returns four sequences in this order
- x_train : The training part of the first sequence
- x_test : The test part of the first sequence
- y_train : The training part of the second sequence
- y_test : The test part of the second sequence

<img width="888" alt="image" src="https://user-images.githubusercontent.com/56888440/227103943-0ea3d676-6020-4044-8142-122ff321ba0a.png">

## SETTING UP PREDICTION

- Using Logistic regression
- Machine Learning classification algorithm that is used to predict the probability of a categorical dependent variable
- Using Pipeline
- a sequence of data processing mechanisms
- Using Countvectorizer 
- Convert a collection of text documents to a matrix of token counts

<img width="898" alt="image" src="https://user-images.githubusercontent.com/56888440/227104147-948f9bc3-7821-4e68-84eb-6267f704fe19.png">

## TRAINING

- Now we are going to use the the prediction data
- By using it to train the logistic regression pipeline

<img width="632" alt="image" src="https://user-images.githubusercontent.com/56888440/227104297-d6b1ce5b-f24c-453f-943e-aad9cfd3a7f1.png">

## MAKING THE PREDICTION

- All we need is a sentence
- From that we pass it to our environment 

<img width="564" alt="image" src="https://user-images.githubusercontent.com/56888440/227104400-d53be6c0-2ff0-4363-a88b-0f47340619a2.png">







