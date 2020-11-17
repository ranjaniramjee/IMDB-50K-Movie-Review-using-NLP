# IMDB-50K-Movie-Review-using-NLP
NLP Dataset: IMDB-50K Movie Review dataset comprising of 50K movie reviews. Please find your dataset from the link - https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/notebooks.
Prepare a python notebook (recommended- use Google Colab) to build, train and evaluate a deep neural network on the IMDB-50K dataset.
1. Import Libraries/Dataset
  a. Import required libraries (recommended- use tensorflow/keras library).
  b. Import the dataset (use Google Drive if required).
  c. Check the GPU available (recommended- use free GPU provided by Google Colab).
2. Data Visualization 
  a. Print at least two movie reviews from each class of the dataset, for a sanity check that labels match the text. 
    b. Plot a bar graph of class distribution in dataset. Each bar depicts the number of tweets belonging to a particular sentiment. (recommended - matplotlib/seaborn libraries) 
    c. Any other visualizations that seem appropriate for this problem are encouraged but not necessary, for the points.
    d. Print the shapes of train and test data.
3. Data Pre-processing 
  a. Need for this Step - Since the models we use cannot accept string inputs or cannot be of the string format. We have to come up with a way of handling this step. 
  b. Please use this pre-trained embedding layer from TensorFlow hub for this assignment. 
  c. Bring the train and test data in the required format.
4. Model Building 
  a. Sequential Model layers- Use AT LEAST 3 dense layers with appropriate input for each. Choose the best number for hidden units.
  b. Add L2 regularization to all the layers.
  c. Add one layer of dropout at the appropriate position.
  d. Choose the appropriate activation function for all the layers.
  e. Print the model summary.
5. Model Compilation 
  a. Compile the model with the appropriate loss function.
  b. Use an appropriate optimizer. 
  c. Use accuracy as metric.
6. Model Training
  a. Train the model for an appropriate number of epochs (print the train and validation accuracy/loss for each epoch). Use the appropriate batch size.
  b. Plot the loss and accuracy history graphs. Print the total time taken for training.
7. Model Evaluation 
  a. Print the final test/validation loss and accuracy.
  b. Print confusion matrix and classification report for the validation dataset. 
8. Hyperparameter Tuning- 
  a. Network Depth: Change the number of hidden layers and hidden units for each layer
  b. Regularization: Train a model without regularization
