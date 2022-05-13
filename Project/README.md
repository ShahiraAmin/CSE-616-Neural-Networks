**Conclusion and Findings:**
I used three different convolutional neural network models for classification of traffic signs and compared their performance. I used TensorFlow to train and test the network using the German Traffic Sign Recognition Benchmark (GTSRB) dataset. The third CNN model achieved the highest test accuracy, followed by the second CNN, and then the third CNN which achieved the lowest test accuracy. The first CNN had the shortest training time per parameter followed by the third CNN, and then the first CNN, which had the longest training time per parameter.

**Repo File Structure:**
I wrote my code using Jupyter Notebook, so all the files in the repository are .ipynb. The repo file structure is as follows:
There are three main files called "main_1.ipynb", "main_2.ipynb", and "main_3.ipynb".

"main_1.ipynb" trains and tests the first CNN model on traffic sign classification using the GTSRB dataset. "main_1.ipynb" calls "create_model_1.ipynb. to build the CNN.

"main_2.ipynb" trains and tests the second CNN model on traffic sign classification using the GTSRB dataset. "main_2.ipynb" calls "create_model_2.ipynb. to build the CNN.

"main_3.ipynb" trains and tests the third CNN model on traffic sign classification using the GTSRB dataset. "main_3.ipynb" calls "create_model_3.ipynb. to build the CNN.

The rest of the .ipynb files in the repo are used by the three main files ("main_1.ipynb", "main_2.ipynb", and "main_3.ipynb") to do the following:
"load_traindata.ipynb" loads the training data.

"load_testdata.ipynb" loads the test data.

"visualize_classes.ipynb" visualizes classes in the GTSRB dataset.

"traindata_statistics.ipynb" prints training data statistics.

"visualize_testdata.ipynb" visualizes the test data.

"shuffle_data.ipynb" shuffles the training data.

"split_data.ipynb" splits the training data into training set and validation set.

"one_hot_encoding.ipynb" performs one hot encoding of the labels.

"configure_network.ipynb" configures the hyper-parameters (learning rate, optimizer, epochs, and batch size).

"train_model.ipynb" trains the model and calculates the training loss, validation loss, training accuracy, validation accuracy, and training time.

"evaluate.ipynb" makes predictions and calculates test accuracy and confusion matrix.

**How to Run the Code:**
To train and test the first CNN model, run the cells in "main_1.ipynb" in order.

To train and test the second CNN model, run the cells in "main_2.ipynb" in order.

To train and test the third CNN model, run the cells in "main_3.ipynb" in order.



> Written with [StackEdit](https://stackedit.io/).
