# Image-classification

This project aims was to explore CNN arichtectures while performing this task of face classification and verification. I learned hyperparameter tuning to measure that the model perform well.

Hyperparameters used and resulted in the best score are:
300 epochs used, batch_size of 128, learning rate of 1e-3, rotation_angle of 30, and horizontal_flip of 0.5.

Data loader functions were optimized using transformation such as rotation, Augmentation, horizontal flipping, etc. All these techniques used to improve the goodness of the data so that the model will generalize well the output.
# Results

classification task Training accuracy was 99.89%
classification task validation accuracy was 90.346%

verification task  accuracy was 54.44%
verification task validation accuracy was 56.944%

# Fine tuning 
Different trial made: batch size: 64,256,128 Roration angle:25,30, Lr = 0.1,0.0001,0.001; brightness: 0.2,0.2,0.2

# code running

To ensure the code are running, Kaggle can be used with GPU runtime.
To run the code cells, start from the beginning.
