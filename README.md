# DogsVsCats-Classifier
It is an image classifier that classifies between a dog and a cat, it is trained using keras using tensorflow backend

The dataset used is the kaggle dataset: https://www.kaggle.com/c/dogs-vs-cats/data
We have reduced the number of images from the orginal dataset, we have considered 1024 images of each class for training and 417 images of each class for validation

The folder structure was:

data1

/train
   /dogs
   /cats
         
 /validation
 /dogs
 /cats
            
 Result:
     We obtained an alidation accuracy of 73.51% for 10 epoch
