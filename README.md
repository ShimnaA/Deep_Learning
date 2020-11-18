***Deep Learning***
    - Artificial Neural Network and Convolutional Neural Network

***Artificial Neural Network***
     - Dataset (Churn_Modelling.csv)
     - Contains details of customers of a Bank - Predict whether Exited or Not

    - Exclude RowNumber,CustomerId,Surname columns
    - Feature Scaling is a must for Deeplearning (we scale all the features)
    - Create 2 hidden layers of 6 neurons
    - compile 
    - Single customer prediction
    - Predict of Test set - 86.75% accuracy
    
***Artificial Neural Network***

    - Dataset (Folds5x2_pp.xlsx)
    - Feature Scaling is a must for Deeplearning (we scale all the features)
    - Create 2 hidden layers of 6 neurons
    - compile 
    - Predict for testset. 
    
***Convolutional Neural Network***
    - Dataset - Containing images of Cats and Dogs
    - Classification model to predict whether the new image is Cat or Dog
    
    - Preprocess data 
        - rescale by 1/255 (to get a value in range 0 to 1)
        - Augment the image by introducing distortion to image inorder to reduce Overfitting 
        - (sheer range, zoom range, horizontal flip)
        - change the target size to 64 x 64
        - Build the archetecture, ie Build the CNN
        - Add a Convolution Layer
        - Add a Pooling Layer
        - Add a second Convolution layer similar to first one
        - Add a Flatten layer
        - Compile the model  adam optimizer, binary_crossentropy loss function, accuracy metrics
        - Train the model - Accuracy on Test Set = 80.55
        - Predict single image.
    