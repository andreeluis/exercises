# Titanic

This is a project to predict the survival of passengers on the Titanic. The dataset is from Kaggle and can be found [here](https://www.kaggle.com/c/titanic/data).

## Data Columns
- `survival`

	If the passenger survived or not.

	**0** = No, **1** = Yes

- `pclass`
	
	The ticket class of the passenger.
	A proxy for socio-economic status (SES) 1st = Upper, 2nd = Middle, 3rd = Lower

	**1** = 1st, **2** = 2nd, **3** = 3rd

- `sex`
	
	Sex of the passenger

- `Age`
	
	Age in years

- `sibsp`
	
	The number of siblings / spouses aboard the Titanic

	The dataset defines family relations in this way:
	- Sibling = brother, sister, stepbrother, stepsister
	- Spouse = husband, wife (mistresses and fiancés were ignored)
	
- `parch`
	
	The number of parents / children aboard the Titanic

	The dataset defines family relations in this way:
	- Parent = mother, father
	- Child = daughter, son, stepdaughter, stepson

- `ticket`
	
	Ticket number

- `fare`
	
	Passenger fare

- `cabin`

	Cabin number

- `embarked`
	
	Port of Embarkation

	**C** = Cherbourg, **Q** = Queenstown, **S** = Southampton

> [!NOTE]
> For training the model, we discard the columns `PassengerId`, `Name`, `Ticket`, `Cabin` and `Embarked` as they are not useful for prediction.

## Usage
To run the project, you need to have the dataset in the `/data` directory. The dataset can be downloaded from [here](https://www.kaggle.com/c/titanic/data).