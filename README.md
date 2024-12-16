# Melanoma-Detection-using-custom-cnn
>
> This project uses a custom CNN to detect melanoma in images among 9 classes. The model predicts with 90% accuracy.

## Table of Contents

- [Melanoma-Detection-using-using-custom-cnn](#melanoma-detection-assignment-using-custom-cnn)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
    - [Algorithms Used](#algorithms-used)
    - [Dataset Information](#dataset-information)
  - [Steps Involved](#steps-involved)
  - [Results](#results)
    - [Baseline Model](#baseline-model)
    - [Augmented Model](#augmented-model)
    - [Final Model](#final-model)
- [Conclusion](#conclusion)
- [Technologies Used](#technologies-used)
- [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Algorithms Used

Convolutional Neural Network

### Dataset Information

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed by the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Steps Involved

- Data Loading
- Baseline Model Building
- Training the Model and testing the model
- Building an augmented model
- Training the augmented model and testing the model
- Countering Class Imbalance with augmentor
- Building the final model
- Training the final model and testing the model
- Verifying the model

## Results

### Baseline Model

Accuracy and Loss charts for the baseline model
![image](https://github.com/user-attachments/assets/bb950e62-03ec-479c-b6e1-812d497c7118)


### Augmented Model

Accuracy and Loss charts for the augmented model
![image](https://github.com/user-attachments/assets/57c3d981-dfc9-4888-b730-b562a385bbc0)


### Final Model

Accuracy and Loss charts for the final model
![image](https://github.com/user-attachments/assets/55cf69be-01ac-4d2d-a3de-daa02f1021df)


# Conclusion

As the accuracy of the model increases, the loss decreases. The final model has an accuracy of 90% and a loss of 0.4 . The model is able to predict the class with a high accuracy.
Augmenting the data and countering class imbalance helped in improving the accuracy of the model.

# Technologies Used

- Python
- Tensorflow
- Keras
- Augmentor
- Matplotlib
- NumPy

# Contact

Created by [@shivanikhobrekar] - feel free to contact me!


