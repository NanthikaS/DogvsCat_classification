DOG VS CAT CLASSIFICATION

OverView:
We are doing dog vs cat classification using Deep Learning. The dataset is from the kaggle competition. Resize the image. Using the mobilenet pre-trained model we classify the images.

Steps:
Join the competition
import the dataset using the Kaggle APi as a list
iterate over the list to find the count of dogs and cats
Resize the original folder for better accuracy
Resize all the images to numpy array
define x and y 
split x_train,x_test,y_train,y_test from the x and y
scaled the x_train and x_test 
using the mobilenet_v2 train the dataset
using adam as  optimizer, SparseCategoricalCrossentropy for loss, accuracy as metric
import the image for prediction.
Atlast the image is predicted as cat or dog.

                                                                                                                          
                                                                                                                          
