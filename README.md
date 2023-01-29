# Healthy and Unhealthy Patient Classification
This is a machine learning project developed to assist an Ayurvedic practitioner in classifying patients as healthy or non-healthy. The project uses patient demographics, image data, and a questionnaire to make predictions using various machine learning models. The repository contains the code and results of the project.


# Introduction
This project was developed for Dr. Kale, an Ayurvedic practitioner, to assist in classifying patients as healthy or non-healthy based on their medical information and image data. The project uses machine learning models to make predictions based on the patient's demographics and the RGB values of images taken using a phone camera.

# Data
The data used in this project was provided by Dr. Kale and includes information about patient demographics (Age, Sex, Rutu, Hb%, RBC, Prakruti, Quetionnaire count(Vata, Pitta, Kapha)) and the RGB values of images taken with a phone camera resolution of 14 pixels. The data has been preprocessed and split into a training set and a testing set.

# Methodology
The project uses a supervised machine learning approach to classify patients as healthy or non-healthy. 
Four different models (KNN, CART, NB, SVM) were trained using the training data, and their performance was evaluated using the testing data.

# Model
The results showed that when only the RGB values were taken into consideration, the accuracy of the models was between 55-60%. However, when the patient's responses to a questionnaire were also taken into consideration, the accuracy of the models increased to between 86-97%.

# Results
The best performing model was [CART] with an accuracy of [97.1429]. The results of the model evaluation can be found in the file.

# Usage
To use the model, follow these steps:

Clone or download the repository to your local machine.
Install the required libraries listed in the [insert file name here] file.
Run the [insert file name here] file to generate predictions for new patients.


# Conclusion
This project shows the importance of considering both patient demographics and image data when classifying patients as healthy or non-healthy. The results demonstrate the potential for using machine learning in Ayurvedic practice to provide more accurate diagnoses and treatment recommendations.
