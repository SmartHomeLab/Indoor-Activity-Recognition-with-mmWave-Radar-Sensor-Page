---
title: Indoor Activity Recognition with mmWave Radar Sensor
layout: home
---

# Indoor Activity Recognition with mmWave Radar Sensor

<div class="author-names">
<a class="author-name" href="https://iastate.edu">Iowa State University</a>
</div>

### Student Participants

<div class="author-names">
<a class="author-name" href="mailto:hobian@iastate.edu">Hongyi Bian</a>
<a class="author-name" href="mailto:mingdian@iastate.edu">Mingdian Liu</a>
<a class="author-name" href="jenhu@iastate.edu">Jieyun Hu</a>
<a class="author-name" href="https://mengw.io">Meng Wang</a>
</div>

### Advisor

<div class="author-names">
<a class="author-name" href="https://www.cs.iastate.edu/chang">Carl K. Chang</a>
</div>

## Overview

<div class="overview">
<div>
<p>
Nowadays, world population is fast aging, which requires heavy investment of time and manpower in daily care, and it has made a huge impact on society and word economy. To caregivers, injury or death caused by fall and declined self-dependence due to dementia such as the Alzheimer’s disease are two main challenges. As reported herein, we devise a human activity recognition (HAR) system which has high potential to handle these issues. In contrast to the traditional systems using RGB camera, the indoor activity recognition system with mmWave Radar offers an advantage with low risk of privacy leakage without losing much recognition accuracy. Taking the data of daily indoor activities as input, four deep learning models are trained and compared leading to an optimized activity classifier. The averaged accuracy of the best model in our test data set reaches 91.87%, which shows its full potential for practical deployment. A simplistic user interface (UI) is also designed to demonstrate the functionality of a well-trained model. To implement distributed deployment, we connect Raspberry Pi to AWS IoT for real-time data collection and processing respectively. A probability threshold of the fall-down action is set by AWS Lambda to trigger an alarm and call for first-aid in time. We hope the system subject to further improvement in this proposal could provide an accurate recognition service to enable remote monitoring for older adults thus significantly reducing the burden and labour cost of caregivers.
</p>
</div>
<div class="overview-image">
<img src="{{ "assets/image/figure.drawio.svg" | relative_url }}" alt="figure">
</div>
</div>

## Video

<div class="video">
<video width="640" controls>
<source src="{{ "assets/video/demo.mp4" | relative_url }}" type="video/mp4">
</video>
</div>

## Paper

[Recognizing Activities of Daily Living to Improve Well-Being](https://ieeexplore.ieee.org/document/7945203)  
Yunfei Feng, Carl K. Chang, Hua Ming
[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7945203)  

[Indoor Activity Recognition with mmWave Radar
Sensor](https://github.com/SmartHomeLab/Indoor-Activity-Recognition-with-mmWave-Radar-Sensor-Static/raw/main/Indoor-Activity-Recognition-with-mmWave-Radar-Sensor.pdf)  
Mingdian Liu, Ge Luo, Shuhan Yang  
[PDF](https://github.com/SmartHomeLab/Indoor-Activity-Recognition-with-mmWave-Radar-Sensor-Static/raw/main/Indoor-Activity-Recognition-with-mmWave-Radar-Sensor.pdf)  
