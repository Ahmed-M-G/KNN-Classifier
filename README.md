# KNN-Classifier
 Using KNN-Classifier for two different tasks
  - ## The first task: Generate a random dataset and apply the concept of KNN classification to it.
    ![image](https://user-images.githubusercontent.com/68587770/202856040-9f6b2748-62e8-4621-af5a-b2a81baa78c9.png)

  - ## The second task: Using the digit dataset and applying the concept of KNN classification to it.
     ![image](https://user-images.githubusercontent.com/68587770/202856329-b08b9baf-52b6-4121-853d-6e0dccd4d9ce.png)

     * This exercise uses the digits dataset - a built-in dataset in sklearn. It consists of 1797 images of the digits from 0 to 9. Each image is of size 8x8. Therefore, the inputs will be of shape (1797, 64). On the other hand, the targets will consist of 1797 rows and 1 column and corresponds to the digit of the specific image.
     * The beginning of the code is implemented. That is, the dataset is loaded in a variable called digits. This variable is defined to help us easily display the digits. The variables inputs and target are also defined.
     * Your task will be to split the data into training and testing (use an 80-20 split) and find the model that best classifies the digits. Do this for two scenarios:
     * ### Scenario 1:
        - With the help of principal component analysis (PCA), the 2 most important principal components have been extracted. Use those to train your model. Display the decision boundaries of the best model. Print out the confusion matrix and the classification report. How is the model performing? Which are the digits that are classified correctly almost always and which are the ones that are amolst never classified correctly?
        
     * ### Scenario 2:
        - In this scenario, use all 64 features (all 64 pixels from the figure). How many neighbors does the best model have now? Study the confusion matrix and the classification report. What is the accuracy compared to the model from Scenario 1?
