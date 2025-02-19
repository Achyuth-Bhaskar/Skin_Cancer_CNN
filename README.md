# Skin Cancer Detection Using CNN
This project aims to build a Convolutional Neural Network (CNN) model to accurately detect melanoma, a type of skin cancer, from images. Early detection of melanoma can significantly reduce skin cancer deaths, and this solution can assist dermatologists in diagnosing skin cancer more efficiently.

# Table of Contents
General Information

Technologies Used

Conclusions

# Acknowledgements

# Contact

General Information
Background: Melanoma is a deadly form of skin cancer that accounts for 75% of skin cancer deaths. Early detection is crucial for effective treatment. This project leverages machine learning to automate the detection of melanoma from skin lesion images.

Business Problem: The project addresses the challenge of manual diagnosis of skin cancer, which can be time-consuming and prone to human error. By automating the detection process, dermatologists can focus on treatment rather than diagnosis.

Dataset: The dataset used in this project contains 2,357 images of skin lesions, categorized into 9 types of skin cancer. The dataset is divided into training and testing sets, with each set containing sub-directories for each class of skin cancer.

# Conclusions
Conclusion 1: The initial CNN model showed signs of overfitting, with high training accuracy but lower validation accuracy.

Conclusion 2: Data augmentation techniques, such as rotation and flipping, helped reduce overfitting and improved the model's generalization.

Conclusion 3: Class imbalance was addressed using the Augmentor library, which improved the model's performance on underrepresented classes.

Conclusion 4: The final model, trained on augmented and balanced data, achieved better validation accuracy and demonstrated improved performance in detecting melanoma.

# Technologies Used
TensorFlow - version 2.12.0

Keras - version 2.12.0

Matplotlib - version 3.7.1

NumPy - version 1.23.5

Pandas - version 1.5.3

Augmentor - version 0.2.12

# Acknowledgements
This project was inspired by the need for early detection of skin cancer to save lives.

The dataset used in this project is from the International Skin Imaging Collaboration (ISIC).

This project was based on TensorFlow's official documentation and various online tutorials on CNN and image classification.