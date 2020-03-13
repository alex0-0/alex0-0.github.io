---
title: "Experiment Log"
---


**Obtain 2 frames/second from the video. Use the object detection result from faster RCNN as ground truth.**

*The metrics can be found [here](https://github.com/rafaelpadilla/Object-Detection-Metrics)*

### SSD

#### Basketball gym 

AP: 45.89% (person)

![basketball](/assets/ssd_basketball_person_rec_pre.png)

mAP: 45.89%

#### India street 

AP: 0.00% (bicycle)

AP: 0.00% (chair)

AP: 0.00% (motorcycle)

AP: 33.63% (person)

![person](/assets/ssd_india_person_rec_pre.png)

AP: 0.00% (umbrella)

mAP: 6.73%


#### Biking 

AP: 59.53% (bicycle)

![bike](/assets/ssd_biking_bike_rec_pre.png)

AP: 61.58% (car)

![bike](/assets/ssd_biking_car_rec_pre.png)

AP: 56.25% (motorcycle)

AP: 29.14% (person)

![bike](/assets/ssd_biking_person_rec_pre.png)

AP: 0.00% (truck)

mAP: 41.30%

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


