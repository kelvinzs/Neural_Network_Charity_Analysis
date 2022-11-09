# Neural_Network_Charity_Analysis

Client wants to predict where to make investments. The goal is to utilize machine learning and neural networks to apply features on a provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. The initial file has 34,000 organizations and a number of columns that capture metadata about each organization from past successful fundi
This new assignment consists of three technical analysis deliverables and a written report. You will submit the following:

Deliverable 1: Preprocessing Data for a Neural Network Model

Deliverable 2: Compile, Train, and Evaluate the Model

Deliverable 3: Optimize the Model

Deliverable 4: A Written Report on the Neural Network Model (README.md)

Tools: Jupyter notebook, Python, Neural networks. 

Results: 
What variable(s) are considered the target(s) for your model? Successfully recieving funding 

What variable(s) are considered to be the features for your model?
Application type, classification, usecase, organization, income amount, status, special considerations, and ask amount.

What variable(s) are neither targets nor features, and should be removed from the input data?
EIN and NAME

Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
In the optimized model, layer 1 started with 110 neurons with a relu activation. For layer 2, it dropped to 80 neurons and continued with the relu activation. From there, the sigmoid activation was a better fit for layers 3 (40 neurons) and layer 4 (30 neurons)

Were you able to achieve the target model performance?
The target for the model was 75%, but the best the model could produce was 72.7%.
<img width="980" alt="Screen Shot 2022-11-09 at 7 03 55 AM" src="https://user-images.githubusercontent.com/80330988/200827261-1b128044-c247-4f0d-80aa-bc4442109cc9.png">

What steps did you take to try and increase model performance?
Increasing the number of neurons and layers. Other activations were tried

SUMMARY
The relu and sigmoid activations yielded a 72.7% accuracy, which is the best performing model. I would suggest attempting the random forest classifier as it is less influenced by outliers.

