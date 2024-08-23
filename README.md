# Flower Recognition Using CNN

This machine learning project leverages a Convolutional Neural Network (CNN) to identify images of flowers. The model has been trained on a dataset containing five types of flowers: "rose, daisy, dandelion, sunflower, and tulip". If you upload an image, even one downloaded from Google, the model will predict the flower's name, provided it belongs to one of these five categories.

## Project Overview

- Model: The Convolutional Neural Netwoek model has been carefully designed and trained to accurately classify images of the five selected flower types.
- Dataset: The dataset includes images of the following flowers:
  - Rose
  - Daisy
  - Dandelion
  - Sunflower
  - Tulip
- User Interface: Streamlit is used to create a simple and interactive user interface where users can upload images and view predictions.
- Running the Application: To run the application, (app.py) file navigate to the directory containing your project files in VS Code or any other terminal. Use the following command to start the app:
  streamlit run app.py

  The dataset initially contains a total of 4318 images, which include 5 samples. To increase the size of the dataset, I performed data augmentation so that the model can  trained or learned  more accurately and will predict  the results  with more accuracy .
