# Neural_Network_Charity_Analysis

Beks has come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

-EIN and NAME—Identification columns

-APPLICATION_TYPE—Alphabet Soup application type

-AFFILIATION—Affiliated sector of industry

-CLASSIFICATION—Government organization classification

-USE_CASE—Use case for funding

-ORGANIZATION—Organization type

-STATUS—Active status

-INCOME_AMT—Income classification

-SPECIAL_CONSIDERATIONS—Special consideration for application

-ASK_AMT—Funding amount requested

-IS_SUCCESSFUL—Was the money used effectively

## What we're Creating

This new assignment consists of three technical analysis deliverables and a written report.We submited the following:

**Deliverable 1: Preprocessing Data for a Neural Network Model**

Using Pandas and the Scikit-Learn’s StandardScaler(), we preprocess the dataset in order to compile, train, and evaluate the neural network model later in Deliverable 2.

![df_head](https://user-images.githubusercontent.com/92646311/185833971-e4651275-2f32-4681-9b8f-5852cdec9e93.png)

![split_scale](https://user-images.githubusercontent.com/92646311/185834021-726f4e52-e433-4640-9865-b0c4763025ee.png)

**Deliverable 2: Compile, Train, and Evaluate the Model**

Using our knowledge of TensorFlow, we designed a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. We will need to think about how many inputs there are before determining the number of neurons and layers in the model. Once we've completed that step, we compiled, trained, and evaluated our binary classification model to calculate the model’s loss and accuracy.

![model_accuracy](https://user-images.githubusercontent.com/92646311/185833997-5992eb40-00fd-41e3-a65b-2c8ddc7f4414.png)

**Deliverable 3: Optimize the Model**

-Optimize your model in order to achieve a target predictive accuracy higher than 75% by using any or all of the following:

-Adjusting the input data to ensure that there are no variables or outliers that are causing confusion in the model, such as:

-Dropping more or fewer columns.

-Creating more bins for rare occurrences in columns.

-Increasing or decreasing the number of values for each bin.

-Adding more neurons to a hidden layer.

-Adding more hidden layers.

-Using different activation functions for the hidden layers.

-Adding or reducing the number of epochs to the training regimen.

**The following variables are removed from input and data.**

-NAME

-EIN

-USE_CASE

-SPECIAL_CONSIDERATIONS

### Attempt1

![attempt1](https://user-images.githubusercontent.com/92646311/185833859-0b6370d7-2e32-4a29-ac1b-ebc204585851.png)


![attemp1_accuracy](https://user-images.githubusercontent.com/92646311/185834811-ac88e80e-a8cd-4825-812c-da43645e774d.png)


### Attempt2

![attempt2](https://user-images.githubusercontent.com/92646311/185833885-00221205-3696-4a39-84cc-e49ee41c0761.png)

![attempt2_epoch](https://user-images.githubusercontent.com/92646311/185833897-9bead297-b09a-41bd-b35e-0d0433f22268.png)

### Attempt3

![attempt3](https://user-images.githubusercontent.com/92646311/185833944-ae4317d3-592b-4702-b0a6-8d1f3c811082.png)

![attempt3_epoch](https://user-images.githubusercontent.com/92646311/185833952-4ba957c3-9c6f-4274-a249-8e60fd32b5e2.png)

# Summary

we performed three attempts to re_evaluate, and took various steps to optmize the model accuracy score. By observing the each attempt accuracy score, attemp1 would be the first recomendation with the accuracy of 72.7% and less loss compared to other attempts.



