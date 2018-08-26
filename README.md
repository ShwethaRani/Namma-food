# Namma-food
    The main goal and functionality of this application is to recognize common indian food items from the uploaded images and to predict the caloric value of the food combination.
    We've initially imported the most common ImageNet Dataset and trained the system using the predefined Inception-v3 architecture,applied with Tensorflow.
    Then, we've created three new datasets namely IDLY, DOSA, and POORI. With these datasets, we've applied "Transfer Learning". For this, the top three levels/layers of the training process is removed and the created datasets are replaced in place of the older ones.
    Now, the system is retrained with the new created datasets, inorder to recognize the new training classes.
    Another dataset containing the food values and the corresponding caloric values is created in the same directory.
    Now, the output obtained from the previous image recognition is mapped with the corresponding value in the caloric value data set(CSV file).
    The result can be displayed with the identified food item and the corresponding caloric value
    For further enhancement, keras can be used for UI and the system can be trained with more and more datasets. Combinations of food items can be identified, and the total caloric value can be obtained.
    Further, the system can also check whether the daily intake exceeds the stipulated amount of calories.
    
    For this system, we cam up with the usage of 'Transfer Learning' as it was suggested as more easy to implement and more efficient than building training systems from scratch.
    For more effecient systems, datasets containing large number of training data can be used. For this application, we've used only around 100 images for training a class. For more effecient recognition, atleast 1000 images can be used.
    
    
