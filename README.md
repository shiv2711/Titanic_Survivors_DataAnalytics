# Titanic_Survivors_DataAnalytics :snowflake:
> In this project i used python to do Analytics about the Titanic Dataset.

In this project i import following module 
<li>numpy
<li>pandas
 
## WHAT I DO IN THIS PROJECT :question:
 
First i use csv file to import data.
  
i used pandas read_csv function to read the csv file in python and pandas DataFrame method to convert file into the data frame.
 
  
  
## DESCRIPTION OF THE ATTRIBUTES OF THE DATASET :point_down:
  
Pclass: Passenger Class ( 1 = 1st, 2 = 2nd, 3 = 3rd)

survival: Survival(0 = No, 1 = Yes)

name : Name

sex : Sex

age : Age

sibsp : Number of Sibling/Spouses Aboard

parch : Number of Parents/Children Aboard

ticket : Ticket Number

fare : Passenger Fare( British pound )

cabin : Cabin

embarked : Port of Embarkation ( C = cherbourg, Q = Queenstown , S = Southampton)
  
  
  
## HANDELING NULL VALUES :muscle:
  
Dataset may contain many rows and columns for which some values are missing. We can't leave those missing values as it is.
  
  1. Either drop the entire row or column.
  2. Fill the missing values with some appropriate value ex. mean of all the values for that column may do the job.
  
> So we seprate those column having more than 35% of the values missing in the dataset.Because they wan't halp us to do analysis.Then simply drop that column.
  
> So in this case we seprate Cabin column and drop it.And in age we set the avg value.And in Emabarked Which value having max count we set that value to null field.
   
### NOW WE GOOD TO GO FOR ANALYTIC :white_check_mark:
 
### FINDING CORRELATION :bar_chart:
  
> After finding correlation between various field we find somthing.

## CONCLUSION :mortar_board:
  
<li>Female passenger were prioritized over men.
<li>People with high class or rich people have higher survival rate than other. The hierarichy might have been followed while saving the passangers.
<li>Passengers travelling with their family have higher survival rate.
<li>Passenger who borded the ship at Cherbourge, survived more in proportion then the others.
 
Hope you enjoy it :heart:.

PRFILE : [:snowman:](https://github.com/shiv2711)
