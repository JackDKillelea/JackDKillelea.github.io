---
title: "Machine Learning - Real Time Object Detection"
excerpt: "My first attempt at real time object detection, using python"
collection: portfolio
---

In this project, I set out to implement real time object detection, using my webcam and python to determine what kind of object was being shown on the webcam. 

I achieved this by using cv2 to capture my webcam, and overlay the information. I used ultralytics to do the actual object detection, firstly I trained one of their AIs using a few of my own images and then I ended up using one of their pre-trained models instead because it worked slightly better (and had more test data than I could give it).

During this, I learnt how to overlay information on a cv2 camera, I also learnt how to detect objects given a basic pre-trained model.

The source code is available here for review [here.](https://github.com/JackDKillelea/ml-object-detection)