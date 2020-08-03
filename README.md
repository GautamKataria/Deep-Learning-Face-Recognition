# Face-Recognition-from-scratch

This repository houses the code for performing  face recognition classification from scratch

### SETUP:
##### First download the following files 
##### Then make the following folders :- 
##### Images
##### Datasets -> Train, Test -> folder with name of the person -> data (pictures)
#####
### Collecting Data:
##### First run the face_recog_data file which is gonna create image dataset for you by detecting and localizing your face
##### you can adjust the number of pictures you want by changing count values.
##### It stores the pictures it takes to the "Images" folder.

##### Move the pictures to Datasets -> Train, Test -> folder with name of the person -> data (pictures)
#####      
##### Now, run the face_Recognition python file to make a deep learning CNN VGG16 model using transfer learning.
##### Which gives us more than 90% accuracy which is amazing.
##### The model will be saved in the same directory as a .h5 file

##### Now, run the facefrontend file to see the end product which works to detect and recognize/ classify faces and shows the result to you in realtime.
##### Face recognition is an important application of deep learning and computer vision and can be used in many industries.
