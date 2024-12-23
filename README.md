# ****** Datasets ******
- [YouTube Faces DB](https://www.cs.tau.ac.il//~wolf/ytfaces/): a face video dataset for unconstrained face recognition in videos
- [UCF101](https://www.crcv.ucf.edu/data/UCF101.php): an action recognition data set of realistic action videos with 101 action categories
- [HMDB-51](https://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/): a large human motion dataset of 51 action classes
- [ActivityNet](http://activity-net.org/): A large-scale video dataset for human activity understanding
- [Moments in Time](https://arxiv.org/abs/1801.03150): A dataset of one million 3-second videos



# ****** Representation Learning / Tokenization ******
There is not much research going on in Video space and hence there is no large model yet ...





# **********  Non-Generative Downstream Tasks (Supervised Learning)  **********

## Video Level Tasks
1. Video Classification Task

## Frame Level Tasks
1. Object Tracking : This is nothing but doing object detection on each frame. We have already seen how to do frame wise tasks here, you can use a similar approach

   - Method 1 : Using Image Model
     
     a. Create a model which can perform image detection (eg YOLO8)
     
     b. Divide the video into frames
     
     c. Apply the above developed image model (a) for each frames in the video
     
     d. Combe all the predictions for each image to form and video !!
     
   - Method 2 : Frame Based Video Model

   https://www.youtube.com/watch?v=DaULLeq_AAU
   
3. Key Point Detection






# **********  Generative Downstream Tasks (UnSupervised Learning)  **********

1. Video2Video Data Augmentation Task
   
https://www.youtube.com/watch?v=0K56LA821ys

https://www.youtube.com/watch?v=zSC145iNzE4
