# Retrain_Inception
This project uses google pretrained inception model and add retrain it using provided images to add new classes.

>> To retrain model

     1) Use docker or install dependencies of tensorflow.
     2) Clone tensorflow/tensorflow and retrain using retrain.py ( see documentation in tensorflow documentation)

>> To classify 
     1) Replace label.txt , output by your retrained output.
  
 This project basically takes excel file as input and gives output a excel file with heighlighted rows of positive 
 class ( In this project Fundus). You may need to do some tweaking to classify.py to make it run according to your
 need.
