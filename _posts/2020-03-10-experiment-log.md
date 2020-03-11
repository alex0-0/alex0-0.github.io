---
title: "Experiment Log"
---


** Obtain 2 frames/second from the video. Use the object detection result from faster RCNN as ground truth. ** 

* The metrics can be found here [[https://github.com/rafaelpadilla/Object-Detection-Metrics#metrics|precision-recall]] *

### Compare the frame with its previous frame(i.e., groundtruth is taken half second ago) 


#### Basketball gym 
AP: 53.71% (person)

![basketball](/assets/basketball_rec_pre.png)

mAP: 53.71%

#### India street 
AP: 0.00% (bicycle)

AP: 0.00% (chair)

AP: 11.11% (motorcycle)

![india](/assets/india_moto_rec_pre.png)

AP: 59.97% (person)

![person](/assets/india_person_rec_pre.png)

AP: 16.67% (umbrella)

mAP: 17.55%

#### Biking 

AP: 43.07% (bicycle)

![bike](/assets/biking_bicycle_rec_pre.png)

AP: 8.00% (car)

![car](/assets/biking_car_rec_pre.png)

AP: 21.67% (motorcycle)

![moto](/assets/biking_moto_rec_pre.png)


AP: 49.96% (person)

![biking_person](/assets/biking_person_rec_pre.png)

AP: 0.00% (truck)

mAP: 24.54%


