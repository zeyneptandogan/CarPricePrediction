# CarPricePrediction

  In this project, the goal is to predictthe selling price of a car, given 12 features. The data consists of information
of 60,000 cars and 12 features such as make, model, age.

### Features:
  -  ID (Unique id number for a given sample) 
  -  brand
  -  model
  -  year (year of production)
  -  transmission 
  -  mileage (how many miles has this car been used)
  -  fuelType
  - mpg (fuel consumption; miles per gallon)
  - engineSize
  - tax
  - Price (target label)

  First of all, the missing values are filled by considering average values or maximum occured ones in the dataset for each attribute. After that, the categorical attributes are converted to numeric by using one hot encoding. Other encoding mechanisms (target encoding and label encoding) are also tried in order to see the effect on the prediction performance. As models; XGBoost, AutoML and RFE are implemented. XGBoost gives the best mean absolute error compared to other models. By changing its parameter, it is tried to find the best model for the prediction problem.
