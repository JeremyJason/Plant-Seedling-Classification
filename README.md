# Plant-Seedling-Classification
Automated Plant and Flower Species Classification from Photographs

Project Desc:

The aim of this project in the domain of Botanical Research is to develop an automation solution that can accurately classify plant species from photographs. University X has invested in curating a dataset of sample images, consisting of images from 12 different plant species. The objective is to create a classifier capable of determining the species of a plant based on a given photo.

The project is divided into three main tasks, with a total score of 30 marks. In the first task, the focus is on importing and understanding the data. The "plant-seedlings-classification.zip" file is extracted, and the images from the training folder are mapped to their respective labels to create a DataFrame. Additionally, a function is written to select and display random images along with their corresponding species labels.

In the second task, data preprocessing is performed. The DataFrame is used to create input features (X) and encoded labels (Y). The shape of all the images is standardized, and normalization is applied to ensure consistency and optimal model performance.

The third task involves model training. The data is split into training and testing sets, and a new convolutional neural network (CNN) architecture is designed to train the model. The model is trained on the training data and validated on the test data. To evaluate the model's performance, a random image is selected, and both the actual label and predicted label are printed.

In the second part of the project, the focus shifts to flower classification. University X has curated a dataset of images from 17 plant species. The objective is to experiment with various approaches to train an image classifier for predicting the flower species from a given photo.

The first task involves importing and understanding the data from the "oxflower17" dataset using the tflearn library. The dataset is split into input features (X) and labels (Y), and the number and shape of the images are printed. The count of each class is also determined.

Next, image exploration and transformation are performed for learning purposes. Random images are displayed, and a specific image is selected and transformed into grayscale format. Filters are applied to sharpen and blur the image, and the differences between the original and transformed images are observed.

The final task focuses on model training and tuning. The data is split into training and testing sets, and performance metrics are evaluated for models trained using supervised learning algorithms, neural networks, and basic CNNs. The best performing model is used to predict the class/label of a given image ("Prediction.jpg"), and the predicted label is shared.

Overall, this project aims to leverage machine learning techniques to automate plant and flower species classification based on photographs, facilitating botanical research and analysis.
