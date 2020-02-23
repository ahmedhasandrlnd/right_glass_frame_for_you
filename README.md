# Glass Frame Preview

<a id='index'></a>
## Table of Contents
- [Project Overview](#overview)
- [How AI works](#works)
- [Usage Instructions](#run)
  - [Data Cleaning](#cleaning)
  - [Training Classifier](#training)
  - [Starting the Web App](#starting)
  	- [Running in localhost](#local)
  	- [ngrok Deployment](#ngrok)
- [Conclusion](#conclusion)
- [Software Requirements](#sw)
- [Files](#files)
- [Credits and Acknowledgements](#credits)


<a id='video'></a>
**_Video Demo of the [deployed App](http://exampleframe.com.s3-website.ca-central-1.amazonaws.com/)_**
![Right Frame Preview](gif/Glass_frame_preview.gif)
<hr/> 

[Back to Table of Content](#index)


<a id='overview'></a>
## Project Overview
When someone wants to get a new glass frame, he/she has to go through a process of trial and error. Maybe he/she finds some eyeglasses attractive on display in the optical shop, but not so great when he/she try them on. Depending on face shapes, skin tones, hair color and eye color, a certain glass frame looks awesome to a cetain person. So, sometimes it become quite hard for a person to choose a right glass frame in a optial shop.<br/>
Artificial Intelligence (AI) can come as rescue in this scenario. AI is already changing almost every spheres of our lives. With the recent advancement of deep learning technology and easily available cloud computing power, we can leverage AI to help us choose the right frame for us. This webapp will show a basic usage of AI to help a person to choose a right glass frame virtually without all the hassels and dilemma.  <br/>
<hr/> 

[Back to Table of Content](#index)
 
<a id='works'></a>
## How AI works here
All the input images of this webapp are taken from https://thispersondoesnotexist.com/, but it will work with any passport sized photograph. In the first step, 35 facial landmarks are estimated from the face of the image. Then a transperant background glass frame is superimposed on the face using the guide of these facial landmarks.  <br/>
![Steps](images/steps.JPG)
<hr/> 

[Back to Table of Content](#index)