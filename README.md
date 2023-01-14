## Problem Statement :
Predicting the facial keypoints to be used detection facial points regions

## Installations
This project was written in Python, using Jupyter Notebooks some of them using Google Colabs. 
The needed Python packages and libraries for this project are:

- pandas
- numpy
- matplotlib
- openCV
- Tensorflow


## File Descriptions
contains :
-  `load_scaled_normalized_augmented_data.ipynb`: download the data and scale , normalize and augment the images and save the training and testing data in numpy_file.npy 

-  `Facial_Keypoint_Detection_modelling.ipynb` : build a deeplearning model able to predict the coordinates of the facial keypoints 

-  `use_the_model.ipynb` : use the model to predict the keypoints coordinates on the frames from the images and them use it to do some fun like placing sunglasses in the right places.

-  `Data` :
    - 1. Training folder: Contains Training images
    - 2. Test folder: Contains Testing images
    - 3. test_frames_keypoints.csv
    - 4. training_frames_keypoints.csv

-  `Fun_imgs` :
    - 1. sunglasses.png
    - 2. moustache.png
