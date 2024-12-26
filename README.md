# ****** Representation Learning / Tokenization ******
There is not much research going on in Video space and hence there is no large model yet ...





# **********  Non-Generative Downstream Tasks (Supervised Learning)  **********

## a. Video Level Tasks
1. [Video Classification Task](https://khetansarvesh.medium.com/video-classification-fc07152ad770)

## b. Frame Level Tasks
1. Object Tracking : 
This is nothing but doing object detection on each frame of the video. We have already seen how to do frame wise tasks here, you can use a similar approach

   - Method 1 : Using Image Model
     
     a. Create a model which can perform image detection (eg YOLO8)
     
     b. Divide the video into frames
     
     c. Apply the above developed image model (a) for each frames in the video
     
     d. Combe all the predictions for each image to form and video !!
     
   - Method 2 : Frame Based Video Model

   https://www.youtube.com/watch?v=DaULLeq_AAU
   




# **********  Generative Downstream Tasks (UnSupervised Learning)  **********

1. Video2Video Data Augmentation Task
   
https://www.youtube.com/watch?v=0K56LA821ys

https://www.youtube.com/watch?v=zSC145iNzE4

https://www.youtube.com/watch?v=KAYYo3lNOHY
