1- Separate 80% of the dataset for training dataset and 20% for test dataset.

2- Create artificial images with data augmentation including (flipping, histogram equalization, rotation, translation, shearing and etc.) and add them to the train set.

3- Display the total number of dataset color images after the data augmentation step.

4- Create a Convolutional Neural Network (CNN) according to the following structure:

![image](https://github.com/minailkhani/Some-Image-Processing-Projects/assets/83788223/e3ddabd0-7000-48bf-b28b-2c77293a107d)


5- Training the model with the following parameters on the dataset:


| Batch size        | Number of epochs   | Learning rate | Loss function             |
|-------------------|--------------------|---------------|---------------------------|
| 100               | 500                | 0.0001        | Binary Cross Entropy       |


5- Display the variation of each epoch in training accuracy and loss function.

6- Display model performance metrics including confusion matrix, loss, accuracy, precision, recall, and specificity.

7- Try another model.
