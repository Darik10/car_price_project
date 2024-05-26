# Car Price Project
A practical project intended to predict a car prices based on given variables.
## **Project Overview:**
We are going to work on a car price peroject posted in [Kaggle](https://www.kaggle.com/). I am not a Kagglist, but for me [Kaggle](https://www.kaggle.com/) is a place where I go to; when I need to pull some data sets to pratice with. 

I have found a data set named  [**Car Price Prediction**](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction) in there, so I decided to pic the whole project and try to solve the problem out there. Let's start it.

To solve this problem I am going to follow the followig steps:-
 - 1st undrestand the problem:
   - What is the problem(research question)? and what is the bigger goal behind it (the business goal).
   
 - 2nd Write down a project proposal:
   - plan the work.
   - break down the work into milestones and smaller tasks.
   - estimate the scope for each milestone.
   - document the project proposal.
   
 - 3rd But the plan in action:
   - follow the plan.
   - make a sub-plan for each task.
   - make sure that each task is done on time.
   - plan for the next move.
   - share your work.

## Step1:  Undrestanding the Problem
###    Problem Descrription
As mentioned in this [Car Price Prediction Project](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction) posted on [Kaggle](kaggle.com), a Chinees automobile company named Teclov_Chinese was aspiring to enter the US market. They were planing to setup a manufactering unit in US, and to produce cars localy; to give competition to their US and European counterparts.

So they need to undrestand the factors effecting the price of cars in the US Market. 

####         Breifly
- the company wants to know:
  - Which variables are significant in  predicting the price of a car.
  - How well those variables describe the car price.


#### Business Goal
The biger idea behind this project is to model the car price variable with the other correlated/associated independent variables. So the managemnt will undrestand how different features of cars effect its price. They will use the model for deciding what designs of cars to produce inorder to meet certain price levels.

**Note:** This project was posted 4 years ago on [Kaggle](kaggle.com), but for now it is enough for me to play with it.

## Step 2: Project Proposal

Before jumping to writing a project prosal, I think it is useful to discus about things like:
 - What is totally asked?
 - What kind of data will be used? What sources of data are availabe?
 - What are the required variables? 
 - What types of analysis and models might be useful? and many more questions a like.
 
For now, we are already familiar with the business problem; and there is a pre-collected servay data which is planed to use for this project. When it comes to the required variables, we would assign the required variables during the proccess; cause all the effecting variables of the car price should be included. And since we had a prediction task, we would use a predictive model; a multiple linear regression is recomended for this task. We will also try to apply other complex predictive models, inorder to campare the results and select the most suitable one.


### <center>Car Price Project Proposal </center>

|Milestone|Tasks|Outcome/Deliverables|Estimated Time|
|---------|----|---------------------|--------------|
|  |Project Workflow is outlined|||
|  Milestone One |Data is gathered| updates are shared | Two weeks |  |
|| Software/hardware needs are identified| |  | 
|----------------|----------------------|-------------------|------------|
|  | Data is formated, cleaned and prepared|  |   |
|Milestone Two| EDA is applied| Summery report is produced| Two weeks|
|  | Descriptive statistics is applied| updates are shared| |
|   | Features are selected| |  |
|----------------|----------------------|-------------------|------------|
|  |Hypothesis testing is applied|  |  |
|  |Modeling and machine learning decissions are finalized| | |
|Milestone Three| Model is constructed| updates are shared|Three weeks|
|  | Model is evaluated, tested and retested for accurecy| | |
|----------------|----------------------|-------------------|------------|
|  |Results are finalized| executive summary is produced |  | |
|Milestone Four| Findigs are shared| Visualizations|One week|
|   |Feedback is incorporated| Results|  |


## Milestone One
1. __Project workflow:__ Our project steps and tasks are outlined on the proposal shown above.
2. __Data:__ We are goin to use these data sets [Car Price Data Sets](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction) posted at [Kaggle](https://www.kaggle.com).
3.__Hardware/Softwares:__ We are goin to use My laptob and Python with its data science libraries such as (numpy, pandas, seaborn, matplotlib, sikit-learn), we will also use Jupyter-notebook to edit and run our code. in addition to that we will use one BI tool, either Power BI or Tablue.

## Milestone Two

#### 1. Cleaning, formating and preparing the data. (Part One)
It's crucial to clean and format the data before doing anything with it, so the data cleaning process that we gon flow will look like this:-

 1. Exploring and Undrestaning the raw data:
  * Checking for general shape (number of rows and columns in the data.)
  * checking for the column names.
  * checking for data types for each column.
  * checking for errors made during the data entry (un-expected values).
  * checking for null values.
  * checking for outliers.
  * checking for duplicates.
**Note:** All the work can be found in the code section.
