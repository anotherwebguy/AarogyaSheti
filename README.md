<div align="center"> 
  <div > 
    <img src="https://user-images.githubusercontent.com/66346161/139520588-5d321bc5-daa3-4d8a-ae95-7667d81c98f5.png">
    <h1>AarogyaSheti App</h1>
  </div>  
  <div align="center">
<!--     <a href="https://github.com/anotherwebguy/AarogyaSheti"><img src="https://badges.frapsoft.com/os/v1/open-source.svg?v=103"></a>
    <a href="https://github.com/anotherwebguy/AarogyaSheti"><img src="https://img.shields.io/badge/Built%20by-developers%20%3C%2F%3E-0059b3"></a>
    <a href="https://github.com/anotherwebguy/AarogyaSheti"><img src="https://img.shields.io/static/v1.svg?label=Contributions&message=Welcome&color=yellow"></a>
    <a href="https://github.com/anotherwebguy/"><img src="https://img.shields.io/badge/Maintained%3F-yes-brightgreen.svg?v=103"></a>
    <a href="https://github.com/anotherwebguy/AarogyaSheti"><img src="https://img.shields.io/badge/PR's%3F-Welcomed-brightgreen.svg?v=103"></a><br> -->
    <a href="https://github.com/anotherwebguy/AarogyaSheti/watchers"><img src="https://img.shields.io/github/watchers/anotherwebguy/AarogyaSheti?style=flat"></a> 
    <a href="https://github.com/anotherwebguy/AarogyaSheti/graphs/contributors"><img src="https://img.shields.io/github/contributors/anotherwebguy/AarogyaSheti?color=brightgreen"></a>
    <a href="https://github.com/anotherwebguy/AarogyaSheti/stargazers"><img src="https://img.shields.io/github/stars/anotherwebguy/AarogyaSheti?color=0059b3"></a>
    <a href="https://github.com/anotherwebguy/AarogyaSheti/network/members"><img src="https://img.shields.io/github/forks/anotherwebguy/AarogyaSheti?color=yellow"></a>
    <a href="https://github.com/anotherwebguy/AarogyaSheti/issues"><img src="https://img.shields.io/github/issues/anotherwebguy/AarogyaSheti?color=0059b3"></a>
    <a href="https://github.com/anotherwebguy/AarogyaSheti/issues?q=is%3Aissue+is%3Aclosed"><img src="https://img.shields.io/github/issues-closed-raw/anotherwebguy/AarogyaSheti?color=yellow"></a>
    <a href="https://github.com/anotherwebguy/AarogyaSheti/pulls"><img src="https://img.shields.io/github/issues-pr/anotherwebguy/AarogyaSheti?color=brightgreen"></a>
    <a href="https://github.com/anotherwebguy/AarogyaSheti/pulls?q=is%3Apr+is%3Aclosed"><img src="https://img.shields.io/github/issues-pr-closed-raw/anotherwebguy/AarogyaSheti?color=0059b3"></a> 
  </div>
  <img src="https://diplomatist.com/wp-content/uploads/2020/04/Precision-Farming_footer_07.15.19-1-scaled.jpg">
</div>  
<br>
<div align="center"> A Smart-Farming solution for farmers to ease the process of farming with the help of IOT and ML . It provides the farmers a way to monitor their farms with IOT smart solutions and early plants disease detection through ML. </div>

<!-- ### List of contents

- [Introduction](#introduction)
- [Approach](#aproach)
- [Dataset Description](#dataset-description)
- [Results](#results)


## Introduction
[(Back to top)](#list-of-contents) <br><br>
Plant disease can directly lead to stunted growth causing bad effects on yields. An economic loss of up to $20 billion per year is estimated all over the world. Diverse conditions are the most difficult challenge for researchers due to the geographic differences that may hinder the accurate identification. In addition, traditional methods mainly rely on specialists, experience, and manuals, but the majority of them are expensive, time-consuming, and labor-intensive with difficulty detecting precisely. Therefore, a rapid and accurate approach to identify plant diseases seems so urgent for the benefit of business and ecology to agriculture.<br><br>
In  agriculture products, diseases  are the main  cause for the lessening  in  both  quality  and  production of  the  agriculture products.  Farmers puts their  great effort in picking best  seeds of plant  and also  provide proper environment for the growth of the plant, although there are lot of  diseases  that  affects  plant  result  in  plant  disease. <br><br>
Recognition of the deleterious regions of plants can be considered as the solution for saving the reduction of crops and productivity. The past traditional approach for disease detection and classification requires enormous amount of time, extreme amount of work and continues farm monitoring.

## Aproach
[(Back to top)](#list-of-contents)


#### 1. Choice of deep learning architecture:
* GoogLeNet(Inception_V3)
#### 2. Choice of training mechanism:
* Transfer Learning
#### 3. Choice of dataset type:
* Color
#### 4. Choice of training-testing set distribution:
* Train: 80%, Test: 20% <br>

The inception module uses parallel 1 × 1, 3 × 3, and 5 × 5 convolutions along with a max-pooling layer in parallel, hence enabling it to capture a variety of features in parallel.

## Dataset Description:
[(Back to top)](#list-of-contents)


Plant Village dataset is a public dataset of 54,305 images of diseased and healthy plant leaves collected under controlled conditions ( PlantVillage Dataset). The images cover 14 species of crops, including: apple, blueberry, cherry, grape, orange, peach, pepper, potato, raspberry, soy, squash, strawberry and tomato. It contains images of 17 basic diseases, 4 bacterial diseases, 2 diseases caused by mold (oomycete), 2 viral diseases and 1 disease caused by a mite. 12 crop species also have healthy leaf images that are not visibly affected by disease.

|Name           | No of Classes | Class Names
| ------------- |:-------------:|:-----------------:|
| Apple     |     04        | 'Apple___Apple_scab','Apple___Black_rot','Apple___Cedar_apple_rust' 'Apple___healthy' |
| Blueberry |     01        | 'Blueberry___healthy' |
| Cherry    |     02        | 'Cherry_(including_sour)_Powdery_mildew', 'Cherry_(including_sour)_healthy' |
| Corn      |     04        | 'Corn___Cercospora_leaf_spot', 'Corn___Common_rust','Corn___Northern_Leaf_Blight','Corn___healthy' |
| Grape     |     04        | 'Grape___Black_rot','Grape___Esca_(Black_Measles)','Leaf_blight_(Isariopsis_Leaf_Spot)','Grape___healthy' |
| Orange    |     01        | 'Orange___Haunglongbing_(Citrus_greening)' |
| Peach     |     02        | 'Peach___Bacterial_spot','Peach___healthy' |
| Pepper    |     02        | 'Pepper,_bell___Bacterial_spot','Pepper,_bell___healthy' |
| Potato    |     03        | 'Potato___Early_blight','Potato___Late_blight','Potato___healthy' |
| Raspberry |     01        | 'Raspberry___healthy' |
| Soyabean  |     01        | 'Soybean___healthy' |
| Squash    |     01        | 'Squash___Powdery_mildew' |
| Strawberry|     02        | 'Strawberry___Leaf_scorch','Strawberry___healthy' |
| Tomato    |     10        | Tomato: 'Bacterial_spot','Early_blight', 'Late_blight', 'Leaf_Mold', 'Septoria_leaf_spot', 'Spider_mites','Target_Spot', 'Yellow_Leaf_Curl_Virus', 'Mosaic_virus', 'Healthy' |


![38](https://user-images.githubusercontent.com/66346161/130379553-4803694e-4054-4f71-a4af-1fab8498ddb8.jpg)

## Results
[(Back to top)](#list-of-contents) <br><br>

![Screenshot from 2021-09-02 07-35-07](https://user-images.githubusercontent.com/66346161/131769696-84a71a3f-e8ae-4c74-b562-8bca91aec05e.png)

Acieved an training accuracy of <b> 90.19 </b> and validation accuracy of <b> 91.97 </b>
 -->
