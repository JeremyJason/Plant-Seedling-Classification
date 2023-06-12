# Plant-Seedling-Classification
Automated Plant and Flower Species Classification from Photographs

Project Desc:

Project Description:

The project in the domain of Botanical Research aims to develop an automation solution for University X, which is conducting research on understanding the characteristics of plant and plant seedlings at different stages of growth. The university has already invested in curating a dataset of sample images and now requires a classifier capable of determining the species of a plant from a given photo.

The dataset provided for the project comprises images from 12 different plant species and can be accessed from the source: https://www.kaggle.com/c/plant-seedlings-classification/data.

The overall objective of the project is to create a robust classifier that can accurately predict the species of a plant based on a given photograph. The project is divided into three main tasks, with a total score of 30 marks.

In the first task, the focus is on importing and understanding the data. The 'plant-seedlings-classification.zip' file is extracted either manually or using Python, resulting in an unzipped folder. The images from the training folder are mapped to their corresponding labels to create a DataFrame. This DataFrame consists of three columns: the name of the image, the species/class/type of the image, and the actual image itself. Additionally, a function is implemented to randomly select and display a specified number of images along with their corresponding species labels.

The second task involves data preprocessing. The DataFrame is used to create the input features (X) and labels (Y). The labels of the images are encoded for numerical representation. Furthermore, the shape of all the images is standardized, ensuring uniformity, and the images are normalized for better model performance.

The third task focuses on model training. The data is split into training and testing sets. It is crucial to verify that the shape of the input features (X) is appropriate (No. of images, height, width, No. of channels). If necessary, corrective actions are taken. A new convolutional neural network (CNN) architecture is designed to train the model, taking into account the complexity and variations in plant species. The model is trained using the training data and validated using the test data. To evaluate the model's performance, a random image is selected, and both the actual label and predicted label are printed for comparison.

Through this project, the aim is to provide University X with an automated solution that can effectively classify plant species from photographs, facilitating their research in understanding the characteristics of plants and plant seedlings.
