# Santander-Customer-Transaction-Prediction

This is my second project done on kaggle, I am supposed to predict whether a customer performs a specific transaction or not. In the training data set, there are 200k rows and 202 columns with one stands for transacted or not and one for customer ID, while 200k rows and 201 coulumns in test data. 
I learned a lot from kernels created in kaggle community, and I distinguished the synthetic data from test set and divided it into two parts, then I broght this information in training set to build 200 more new features corresponding to 200 existed features. 
I trained, valdated and tuned the Light Gradient Boosting Machine where I trained with one feature and the one corresponding feature per round, which means 200 rounds.
I submitted and got a score 0.92
