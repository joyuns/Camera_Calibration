# Camera_Calibration
![header](https://capsule-render.vercel.app/api?type=slice&color=auto&height=250&section=header&text=Camera&nbsp;Calibration&fontSize=80)

# Introducing Repository
-This repository contain Distance correction with chessboard images

# How To Operaite
-Load the image.<br/>
-Convert the image to grayscale.<br/>
-Apply median blur to reduce noise.<br/>
-Detect edges using adaptive thresholding.<br/>
-Convert the image to color.<br/>
-Combine the color image with the edges mask.<br/>
-Display the cartoon image.<br/>

# Discussion of Limitations
-The program is that it is difficult to turn various images into cartoon styles.The more complex the details and colors of the image are, the more inconsistent the algorithm's performance becomes. There is also a limit to implementing the specific cartoon style that the user wants. The current program needs to be developed a little more because it goes through a relatively simple process.<br/>

# Demonstration
-카메라 캘리브레이션 과정<br/>
<p align="center">
  <img src="https://github.com/joyuns/Photo_to_Cartoon/assets/90548771/ce581d04-9de7-4730-9fd5-52b0d757de59">
</p>
-카메라 캘리브레이션 결과<br/>
<p align="center">
  <img src="https://github.com/joyuns/Photo_to_Cartoon/assets/90548771/046d7db4-8a27-449b-8ed7-1bcb7f017e54">
</p>
-왜곡 보정 전<br/>
<p align="center">
  <img src="https://github.com/joyuns/Photo_to_Cartoon/assets/90548771/1114d9f4-da3a-4751-b6e1-fbafec74caec">
</p>
-왜곡 보정 결과<br/>
<p align="center">
  <img src="https://github.com/joyuns/Photo_to_Cartoon/assets/90548771/45b62211-69f0-47ec-8793-8eeecb8f99a8)">
</p>
