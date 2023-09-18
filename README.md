
# Traffic Sign Recognition
Traffic Sign Recognition (TSR) is a critical component of modern intelligent transportation systems. It involves the detection and classification of traffic signs from images or videos captured by cameras mounted on vehicles or alongside roads. TSR plays a crucial role in enhancing road safety, assisting drivers and enabling autonomous vehicles to understand and obey traffic rules.


## Problem Statement 
To design and implement a Traffic Sign Recognition (TSR) system that can accurately detect and classify traffic signs from images. The system should perform reliably under varying lighting conditions, weather and traffic scenarios. 



![App Screenshot](https://fnsautoglass.com/wp-content/uploads/2022/10/Traffic-Sign-Recognition3.png.webp)


##  Dataset
#### Follow the steps to download the 'Kaggle.json' file:

    1. Log In to Your Kaggle Account
    2. Navigate to Your Account Setting 
    3. Generate an API Token ()
    4. click on the "Create New API Token" button

This action will trigger the download of a file named "kaggle.json" to your computer.

####  How to load the 'Kaggle.json' file into Google colab / Jupyter Notebook.
Follow the steps:

    1. files.upload('kaggle.json')

    2. !pip install -q kaggle

    3. !mkdir -p ~/.kaggle
       !cp kaggle.json ~/.kaggle
       !chmod 600 ~/.kaggle/kaggle.json

    4. !mkdir traffic_sign_dataset
       %cd traffic_sign_dataset

    5. !kaggle datasets download meowmeowmeowmeowmeow/gtsrb-german-traffic-sign
       %cd ..

    6. !unzip traffic_sign_dataset/gtsrb-german-traffic-sign.zip -d traffic_sign_dataset
       !rm traffic_sign_dataset/gtsrb-german-traffic-sign.zip
       !rm -rf traffic_sign_dataset/Meta
       !rm -rf traffic_sign_dataset/meta
       !rm -rf traffic_sign_dataset/test
       !rm -rf traffic_sign_dataset/train
       !rm traffic_sign_dataset/Meta.csv

## Techniques:
* CNN
* Tensorflow
* Keras

## Conclusion:
The Traffic Sign Recognition project leverages cutting-edge techniques such as Convolutional Neural Networks (CNN) implemented with the help of popular deep learning frameworks like TensorFlow and Keras. This project addresses a critical real-world problem by automating the detection and interpretation of traffic signs, which is essential for enhancing road safety and facilitating autonomous driving.
