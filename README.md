# recognizing-handwritten-digits-using-PyTorch

in this project , we have used a CNN model in order to classify 10 classes of handwritten digits using PyTorch .
In the first file  we have initially preprocessed our dataset.
and then we have built our CNN model ,   and trained it on a training dataset( optimization using gradient descent and as for the loss function we have used the cross entropy). 
after that we have tested our trained model on a new dataset to see its performance ; we have com^puted the loss function and see if it is decreasing or not.
AFTER THAT : we have tried early stopping and also dropout methods in order to improve the model's perfomance ( training optimization)
the early stopping will tell us about the number of epochs needed ,means when we should stop training.

in second file named hyperparameters optimization: i have tried to do the hyperparameters tuning , such as the number of filters(kernels), their size, padding,stride.
so the first step is to find the best hyperparamters, and for this we need to use a validation set. after we have found them we are going to retrain our model with this specific hyperparamters values;and then we will evaluate its performance on a test set.
these hyperparameters plays a crucial role in improving model's accuracy; even its complexity. so finding the best hyperparameters will gives us the best model.( we got a smaller loss function).

