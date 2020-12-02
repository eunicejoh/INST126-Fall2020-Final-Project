# INST126-Fall2020
## Final Project: Data Analysis 
## Nutritional Comparison Tool for Various Cereals
### Group Members: Eunice Oh, Dante Cavalier, Zijing Wang, Jalen Rawles, Noah Shaw

## Overview
Many choose cereal as their breakfast meal and there are various brands and kinds, all of which also have differing nutritional values. In other words, some are healthier while others are not. With nutritional value becoming increasingly more prevalent in society, it’s important for consumers to be health-conscious of what they intake. Furthermore, we wanted to provide a nutrition tool for consumers to research specific cereals, compare multiple cereals, and look for certain cereal that meets their nutritional needs and wants.

Our goal is to provide a comparison of nutritional values of different cereals to inform consumers about their cereal choices as well as encourage healthier eating habits through the displays of charts and graphs.

## How It Works
Our program will aim to help the user complete 3 different tasks through the use of pandas and matplotlibs.

First, the program will display a welcome message.

The 3 different tasks are in the form of questions as follows in this order:
1) “Is there a specific cereal you would like to look at?”
2) “Would you like to compare two cereals?”
3) “Do you have specific needs for cereal?”

Each of these tasks/questions will have their own function.

### search_for_cereal()
The first function our program will have is allowing the user to research information regarding a specific cereal. The user would tell the program what cereal they would like to research, and it would return nutritional and informational data about the cereal such as the manufacturer, how many calories per serving, and how many grams of fat are in it. Our program will also provide visual representations of some of the information using graphs and charts to better convey information to the user. The user can research as many individual cereals as they would like before being prompted with the next function. 

### compare_cereal()
The next capability or program will have is allowing the user to compare data between two different cereals. The user would select two cereals they would like to compare and return the data from both cereals in a format that allows the user to compare them. The user will be able to continue comparing as many cereals as they wish before being prompted with the final question. 

### specific_needs()
The last question our program will ask the user is if the user has any specific needs regarding their cereal choice. For example, if the the user wants to be shown the cereals with the lease amount of sugar or wants cereals from a specific manufacturer, the program will sort the data based on the user's parameters and provide the user with their requested information using charts, graphs, etc. Similarly to the other two functions, the user can do this as many times as they would like. 

After going through all three functions, the program will end with a goodbye message. 

## Updates
### November 17, 2020
- Team held a meeting to discuss project ideas/plans.
- Decided on a data analysis approach
- Collaborated on finding potential CSVs (datasets) and unanimously decided on (https://www.kaggle.com/crawford/80-cereals)
- Created the repository and folders for the code and flowcharts
- Wrote out code for reading and cleaning up the downloaded dataset

### November 24, 2020
- Team held a meeting to discuss and outline project flowcharts
- Created a rough outline of the program
- Team completed flowcharts for all planned functions of the program

### December 1, 2020
- Team held a meeting to discuss code progress as well as distribute coding roles
- Updated the README to include our progress and updates
- Created a new folder for the documents pertaining to the required weekly updates
- Finalized starter code for functions

## Installation
Please have Jupyter Lab or Jupyter Notebook downloaded. Additionally, please have the cereal.csv file on hand. Then, run the ipynb file in a new Jupyter Lab or Notebook.

## Credits
- The dataset was created and shared by Chris Crawford on Kaggle (https://www.kaggle.com/crawford/80-cereals)
