﻿# Vegetables-disease-predict
 The increasing prevalence of vegetable diseases poses a significant threat to agricultural productivity and food security. This project presents an innovative approach to vegetable disease detection using machine learning techniques, specifically employing a Random Forest Classifier algorithm, aimed at providing farmers and agricultural stakeholders with a reliable tool for early diagnosis and intervention. Leveraging the power of Streamlit, we have developed an interactive web application that allows users to easily upload images of vegetables through a user-friendly drag-and-drop feature.The application utilizes the RandomForestClassifier from scikit-learn, an ensemble learning method that builds multiple decision trees during training and outputs the class that is the mode of the classes of the individual trees. This robust classification algorithm is implemented in the model.py file for accurate predictions.To enhance the model's performance, we employ feature extraction techniques, including Histogram of Oriented Gradients (HOG) to capture shape and edge information in the images, as well as color statistics from the HSV color space to better identify disease-specific color patterns. Additionally, a fallback rule-based system is integrated, which utilizes color features to make predictions when the trained model isn't available. This ensures that the application can still provide valuable insights even in the absence of the pre-trained model.This project not only enhances the accessibility of disease detection for farmers but also promotes sustainable agricultural practices by facilitating timely interventions. The combination of machine learning and an intuitive interface through Streamlit makes this tool a valuable resource in the fight against vegetable diseases, ultimately contributing to improved crop yields and food quality. By empowering farmers with knowledge and technology, we aim to foster a more resilient agricultural ecosystem.
