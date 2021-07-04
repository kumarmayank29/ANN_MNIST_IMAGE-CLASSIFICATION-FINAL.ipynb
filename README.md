# ANN_MNIST_IMAGE-CLASSIFICATION-FINAL.ipynb

We are using MNIST dataset which is a dataset consisting of Handwritten Images from 0 to 9.These Numbers are from 0-9 and we need to classify among them so its a multiclass classification problem.There are a total 60000 images consists of digits between 0 to 9.These are all Grayscale Images.Every image in MNIST is 2828 size and total of 784 pixels and all of them are grayscale.(If they would have been colored then dimension would have been 2828*3)

Each Image is 28*28 in Size and total of 784 pixel image .Value of each pixel lies within a range which varies from (0-255) .0 to white and 255 for black color 

x_train[0][12] 12th image with value of array([  0,   0,   0,   0,   0,   0,   0,   0,   0,   0,   0,  11, 190,253,  70,   0,   0,   0,   0,   0,   0,   0,   0,   0,   0,   0, 0,   0], dtype=uint8) value is between 0-255.

The model in this project gives accuracy of 94.33 on test data
![Screenshot (974)](https://user-images.githubusercontent.com/64895688/124388422-866d9880-dd00-11eb-8298-5018f9630666.png)

         
         
         
