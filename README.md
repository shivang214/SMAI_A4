#  SMAI MINI PROJECT:

1. The imagenet tranfer learning model in the porject is **Resnet 18 , Resnet 50 and Resnet 101**.

2. I used the ensemble model for calculating the mean of the age predictions by training the three different versions of resnet.

3. Applied a data augmentation to get better image information for better predictions.

4. The model is trained at 20 epochs which ensures that the model doesnot get overfit and used **Adam optimiser** and **scheduler** .

5. For Fine-tuning freezed and unfreezed some layers so that model can learn better.

6. Lastly rounded off the float values into integer.



## Results:

**5.80670**


## Predicition File:
output.csv