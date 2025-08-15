# Linear Regression Projects

Projects Included:
1. Linear Regression Model A with Application (Chirps per minute and temperature)

Linear Regression Model A Project Overview:
<img width="659" height="298" alt="Screenshot 2025-08-15 114836" src="https://github.com/user-attachments/assets/1a8ce76f-3df1-4d24-bc99-ff2723661db2" />

<img width="724" height="199" alt="Screenshot 2025-08-15 115354" src="https://github.com/user-attachments/assets/9dc2bb6c-59a4-4cb7-a8ab-205b971346f6" />


The core of the LinearRegressionModelA.ipynb notebook is the implementation of the gradient descent algorithm. The model's linear relationship is defined by the simplified equation y=wx. The algorithm follows these key steps to iteratively find the best-fit line:

    Get predictions: The algorithm computes the predicted values y_hat for the input data x using the current value of the parameter w.

    Compute the loss: The loss is calculated as the difference between the true values y and the predicted values y_hat. This is typically measured using a metric like Mean Squared Error.

    Find the gradient: The algorithm finds the gradient of the loss with respect to the trainable parameter w.

    Update parameters: The value of the parameter w is updated by subtracting the gradient obtained in the previous step. This process is repeated until the loss is minimized.

Files:

     LinearRegressionModelA.ipynb
     
     LinRegApplicationExampleA.ipynb

     chirps.xls
