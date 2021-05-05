## Keras-1D-PCA
This code is for excuting PCA and then reducing a dimension of dataset.The prnciple of PCA is like below.

![20210505_142423](https://user-images.githubusercontent.com/71545160/117100080-cb7f5800-adad-11eb-93c8-70cdd1ba3acd.png)


This project contains three-python files.
The description of each file is as follows.

### PCA_going_to_2_dim.py
If you run this code, you can get a figure like below one.
It means that we cannot split data in the two dimension space as a result of PCA.
In this case, you have two-options to enhance the classification performance.
First one is increase the dimension of PCA, 
Sencond one is using LDA(Linear Discriminant Analysis). 
In this project, I'll use the first one. 
Then, we have to check how many dimension to be used for classifying the data perfectly.

![20210505_141306](https://user-images.githubusercontent.com/71545160/117099493-49426400-adac-11eb-9451-aeefaab808f7.png)


### PCA_SVM_classifier_acc_according_to_components.py
In the paragraph above, I said that we should look into how many dimensions to use.
This file deals with it.
Below figure represents that if we use the PCA going to 3-dimension, we can split the data with high performance.  

![20210505_142538](https://user-images.githubusercontent.com/71545160/117100087-ccb08500-adad-11eb-9daf-63a940e15378.png)

### PCA_goint_to_3dim_How_to_split_the_classes.py
This file represents that how data is splited in the 3-dimension space. 
Below figure is the result of this file.
![20210505_142513](https://user-images.githubusercontent.com/71545160/117100084-ccb08500-adad-11eb-82f9-4b6be8666b01.png)
