## Car Price Prediction

#### Problem Statement:
    
    To determine the selling price of a car based on various criterias such as it's age, type of fuel, 
	first or second owner and whether it is automatic or manual.
    
#### Data Description
    
	Data is from Cardekho website in csv format. The csv file was taken from Kaggle.
    
#### Data Validation
    
	In this step, we will validate whether the data provided is good to the standards of it's domain. 
	For eg, if the current price of a car is in negative, then it is a mistake as the price can't be negative, 
	so we will validate such kind of discrepancies.

     
#### Model Training
      
		Model is trained using Random Forest Regression algorithm.
		
     Data Preprocessing: 
        1. Check for null values in the columns. If present, impute the null values.
        2. Check if any column has zero standard deviation and potential dummy variable trap, remove such columns as they don't give any information during 
        model training.
    

## Create a "Procfile" with following content
```
web: gunicorn main:app
```

## to create requirements.txt

```buildoutcfg
pip freeze>requirements.txt
```

## initialize git repo

```
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin <github_url>
git push -u origin main
```

## to update the modification

```
git add .
git commit -m "proper message"
git push 
```
