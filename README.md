# deep-learning-challenge

a. Purpose: Nearal Network was used to identify relationship between input and output data where data is non linear. The data was converted to linear format to use for the model

b. Results
    Data Processing
    - 'IS_SUCCESSFUL' column was used as feature 
    

    Compiling, Training, and Evaluating the Model
    - Multiple iterations were used to train and improve accuracy
    - Iteration 1:
        - Columns EIN and NAME were droppped
        - Hidden layers were trained using 'relu' while output layer using 'sigmoid'
        - Accuracy identified as 73% and output was saved 
    - Iteration 2:
        - Column EIN was dropped
        - To improve efficiency of model, NAME column was converted to binary values using one hot encoder
        - Hidden layers were trained using 'relu' and 'tanh' while output layer using 'sigmoid'
        - Accuracy identified as 72.66% and output was saved 
    - Iteration 3:
        - Column EIN was dropped
        - To improve efficiency of model, NAME column was converted to binary values using one hot encoder
        - Hidden layers were trained using 'relu' and 'tanh' while output layer using 'softmax'
        - Increased hidden layers from 8 to 20
        - Accuracy identified as 72.75% and output was saved 


c. Summary 
    Although goal was achieve accuracy more 75%, after 3 iterations accurancy could not improved more than 73%. To achieve higher accuracy more variables needs to be changed and train the model.