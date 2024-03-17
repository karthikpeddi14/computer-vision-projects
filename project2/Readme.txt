in this project:
1. I have learnt how to work with OS
      we took path of folder which contains empty, non_empty parking lot photos and read it to variables in code.
2. we have done 'imread','resize', which we got from 'skimage'
      from skimage.io import imread
      from skimage.transform import resize
2. learnt what is GridSearchCV - if we give model, parameters and then fit it to training data, it will give set of best combination of parameters from given values
      from sklearn.model_selection import GridSearchCV
3. Learnt about SVC - SVC is a supervised learning model like for example, a linear Regression model
      from sklearn.svm import SVC

we have classified whether the car is present in the parking lot or not after training the best SVC model using GridSearchcv, with a 100% accuracy
