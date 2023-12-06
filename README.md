# Image Classification on CIFAR-10 dataset

CIFAR-10 is a widely used dataset in computer vision, consisting of 60,000 32x32 color images from 10 different classes. The aim is to develop a deep learning model capable of accurately classifying these images into their respective classes.

## Data pre-processing

We have loaded the dataset, normalized the dataset to pixel values between 0 and 1, done some reshaping, observed the dataset by viewing some of the images, done the train test split.

## Learning Models used for the classification task:

### 1. Basic Model
• We have build a basic CNN model, with 3 Convolution layers, 2 Max Pooling layers, used relu activation function on Convolution Layers then
done flattening and used the dense layer with relu activation function and finally the output dense layer is having 10 neurons as our dataset has 10 output labels with activation function as solftmax.

• When we trained this model with training data, we achieved an accuracy of 77.38% percent with 10 epochs and validation data of 10% for each
epoch.

• We achieved Validation dataset accuracy of 68.35%.

• When we tested this model on test dataset we achieved an accuracy of 70.20%.

### 2. ResNet50 Model
• When we trained this model with training data, we achieved an accuracy of 97.29% percent with 10 epochs and validation data of 10% for each
epoch.

• We achieved Validation dataset accuracy of 93.80%.

• When we tested this model on test dataset we achieved an accuracy of 94.17%.

### 3. ResNet101 Model
• When we trained this model with training data, we achieved an accuracy of 98.11% percent with 10 epochs and validation data of 10% for each
epoch.

• We achieved Validation dataset accuracy of 94.65%.

• When we tested this model on test dataset we achieved an accuracy of 94.33%.

## Final Model Selection:
We choose ResNet50 model as our final model and saved the ResNet50 model as its accuracy is nearly equal to ResNet101 model, complexity of
ResNet50 model is less than ResNet101 model and also the training time is significantly less than ResNet101 model.

## Contribution:
• Mohit Agarwala:- Data Preprocessing, Building the ResNet50 model<br />
• Rahul Kumar:- Building the ResNet101 Model, Assisted in data preprocessing<br />
• Combined Work:- Jointly build the Basic Model, assisted eachother whenever required.

