# Binary_Classes_Spectrogram

How to do 2 classes classification on spectrogram dataset?

1. I took the UrbanSound8K dataset from Kaggle and did some preprocessing to output the spectrograms as npy files. Kindly look for my preprocessing at https://github.com/ss47tt/UrbanSound8K_Custom

3. I chose train and test datasets of 2 classes, that is, drilling and jackhammer. There are 450 npy files for each class in train and 50 npy files for each class in test dataset.

4. I used Resnet50 model and sigmoid output layer for the training.

5. I split the train dataset into training and validating datasets of 9:1 ratio respectively.

6. I used ReduceLROnPlateau learning rate scheduler, and early stopping to reduce overfitting.

7. For testing, I used sigmoid layer to output probability for each test file and confusion matrix.
