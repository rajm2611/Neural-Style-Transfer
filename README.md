# introml-project

Introduction:
=============
We see on social media that people like to mix their image with different types of styles. We implemented a sophisticated algorithm using Transfer Learning to implement this style tranfer.

Flow:
=====
we take two images as input. One is the content image(eg:Human Image) and other is the style image. Then using our model we generate a mixed image which adapts contours from content image and colours and texture of the style image. The network tries to minimize the difference between features that are activated for the content-image and for the mixed-image, at one or more layers in the network.


Here, I have used the optimal setting for content-image and style-image(both content and style image will have similar weight in the final image).
=========================================================================
![alt text](https://github.com/kushshah289/introml-project/blob/master/readme%20file/1_1.PNG)
![alt text](https://github.com/kushshah289/introml-project/blob/master/readme%20file/1_2.PNG)
![alt text](https://github.com/kushshah289/introml-project/blob/master/readme%20file/1_3.PNG)<br>
Here, the weight of content-image will be very high in final image as compared to the weight of the style image.
============================================================================================
![alt text](https://github.com/kushshah289/introml-project/blob/master/readme%20file/2_1.PNG)
![alt text](https://github.com/kushshah289/introml-project/blob/master/readme%20file/2_2.PNG)
![alt text](https://github.com/kushshah289/introml-project/blob/master/readme%20file/2_3.PNG)<br>
Here, the weight of style-image will be very high in final image as compared to the weight of the content-image.
============================================================================================
![alt text](https://github.com/kushshah289/introml-project/blob/master/readme%20file/3_1.PNG)
![alt text](https://github.com/kushshah289/introml-project/blob/master/readme%20file/3_2.PNG)
![alt text](https://github.com/kushshah289/introml-project/blob/master/readme%20file/3_3.PNG)<br>
<br>
Node Graph for the Network
==========
![alt text](https://github.com/kushshah289/introml-project/blob/master/readme%20file/graph.png)

