# **Implementing Advanced Models on Labelled and Unlabelled Images (IAM-LUI)**
This project implements image classification using TensorFlow and Keras for two distinct tasks: <br> <br>
  Unlabelled classification of coral reef images <br>
  Labelled classification using the CIFAR-10 dataset

## **Project Overview**
This project aims to demonstrate the versatility of deep learning techniques in image classification tasks. We tackle two different scenarios: <br>

  **Unlabelled Coral Reef Classification:** Using unsupervised learning techniques to categorize coral reef images, potentially aiding in marine biology research and conservation efforts. <br> <br>
  **CIFAR-10 Classification:** A supervised learning task using the well-known CIFAR-10 dataset to classify images into 10 distinct categories, showcasing the model's ability to handle labeled data. <br>

  By addressing both labeled and unlabeled classification tasks, this project highlights the adaptability of neural networks in various real-world scenarios.

## **Installation**
To install the files locally, follow these steps: <br>
  
  Clone this repository to your local machine:
      
    git clone https://github.com/snayak-commits/IAM-LUI.git

## **Dataset Information**
**Coral Reef Dataset:** <br>
The coral reef dataset consists of unlabelled images collected from various reef locations. Images are preprocessed to a standard size of 224x224 pixels. The dataset aims to capture diverse coral species, reef structures, and marine life. <br>

**CIFAR-10 Dataset:** <br>
CIFAR-10 is a widely used dataset in machine learning for image recognition. It consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The classes are: <br>

  Airplane <br>
  Automobile <br>
  Bird <br>
  Cat <br>
  Deer <br>
  Dog <br>
  Frog <br>
  Horse <br>
  Ship <br>
  Truck <br>

This dataset is automatically downloaded when running the CIFAR-10 classification script.

## **Procedure**
This project uses unlabelled images of various coral reef samples and labelled images of the CIFAR-10 dataset. The labelled and unllabeled images are classified, segmented, and visualized. The machine learning model is trained and tested using the data that has been divided into train, test, and validation splits.

## **Features**
  Both Labelled and Unlabelled images are classified, segmented, and appropriately visualized. <br>
  Semantic Segmentation performed for Labelled Dataset <br>
  Visualization of the results.

## **Contributing**
Contributions are welcome! If you have any ideas for improvements or new features, feel free to open an issue or submit a pull request.

## **License**
This project is licensed under the MIT License - see the LICENSE file for details.
