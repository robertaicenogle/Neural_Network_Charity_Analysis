# Neural_Network_Charity_Analysis

## Project Overview
In this project, we'll use deep learning neural networks with the Python TensorFlow platform to analyze charitable donations. The basic method is as follows:
- Process the data for the neural network model
- Train and evaluate the model
- Optimize the model

## Resources
- Data Source: charity_data.csv
- Software: Python, Anaconda, Jupyter Notebook


## Results:
### Deliverable 1: Preprocessing Data for a Neural Network Model
- AlphabetSoupCharity.ipynb file, AlphabetSoupCharity.h5 file

### Deliverable 2: Compile, Train, and Evaluate the Model
- AlphabetSoupCharity.ipynb file, AlphabetSoupCharity.h5 file

### Deliverable 3: Optimize the Model
- AlphabetSoupCharity_Optimzation.ipynb file, AlphabetSoupCharity_Optimzation.h5 file

### Deliverable 4: A Written Report on the Neural Network Model 
Data Preprocessing
What variable(s) are considered the target(s) for your model?
- The column IS_SUCCESSFUL is the target of the model

What variable(s) are considered to be the features for your model?
- The features of the model include APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT

What variable(s) are neither targets nor features, and should be removed from the input data?
- EIN and NAME are identification information and have been removed from the input data

Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
- The model is composed of 80 and 30 neurons within two hidden layers, and two activation functions.

Were you able to achieve the target model performance?
- The target model performance was not acheived

What steps did you take to try and increase model performance?
- Bucketing, organizing values by intervals.


Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
- The accuracy of the deep learning network model was 73%, and did not reach the target 75% accuracy. The model is not outperforming.
- In a binary classification, we may use a supervised machine learning model to combine numerous decision trees to generate an output. This could be evaluated against this deep learning model.
