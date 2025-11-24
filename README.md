# Aim

This project aims to predict the Price of an used Car by taking it's Company name, it's Model name, Year of Purchase, and other parameters.



## How to use?

1. Clone the repository
2. Install the required packages in "requirements.txt" file.

Some packages are:
 - numpy 
 - pandas 
 - scikit-learn

3. Run the "application.py" file
And you are good to go. 

# Description

## What this project does?

- This project takes the parameters of a used car like: Company name, Model name, Year of Purchase, Fuel Type and Number of Kilometers it has been driven.


## How this project does?

1. First of all the data was scraped from Quikr.com (https://quikr.com) 
Link for data: https://drive.google.com/file/d/1zrlMEQupTlejy28RVYx9_L0zBMXAHrGF/view?usp=drive_link

2. The data was cleaned (it was super unclean :( ) and analysed.

3. Then a Linear Regression model was built on top of it which had 0.92 R2_score.

Link for notebook: https://colab.research.google.com/drive/1q_1jRocd8s8cR0lFsjmtM455EtUab1fG?usp=sharing
