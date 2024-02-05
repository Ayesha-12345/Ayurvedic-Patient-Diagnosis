# Healthy and Unhealthy Patient Classification

This machine learning project aids Ayurvedic practitioners in classifying patients as healthy or non-healthy. Utilizing patient demographics, image data, and a questionnaire, various machine learning models make predictions. The repository contains the project's code, results, sample data, and the award-winning Aavishkar research poster.

## Introduction

Developed for Dr. Kale, an Ayurvedic practitioner, this project classifies patients as healthy or non-healthy based on medical information and image data. Machine learning models leverage patient demographics and RGB values from phone camera images.

## Sample Data

<p float="left">
  <img src="https://drive.google.com/uc?export=view&id=1Bi_8hFta8vxA33LoqgCrhjpbxh_6J-2_" width="300" />
  <img src="https://drive.google.com/uc?export=view&id=1u4BVckCR7-BST2QpxnBfPrRh4OpmQ4lC" width="300" />
</p>

## Data

The provided data from Dr. Kale includes patient demographics (Age, Sex, Rutu, Hb%, RBC, Prakruti, Questionnaire count(Vata, Pitta, Kapha)) and RGB values of images (14 pixels resolution). The preprocessed data is split into training and testing sets.

## Methodology

A supervised machine learning approach classifies patients using four models (KNN, CART, NB, SVM). Models are trained on demographic and image data, and performance is evaluated on testing data.

## Model

Results show that considering both RGB values and questionnaire responses significantly improves accuracy (86-97%). The best-performing model, [CART], achieved an accuracy of [97.1429].

## Poster Presentation

The project won the Aavishkar research poster presentation competition at the college, zonal, and university levels. 
<p align="center">
  <img src="PosterPresentations.com-100CMx100CM-Template-Chamberlain_page-0001.jpg" alt="Poster Presentation" />
</p>


