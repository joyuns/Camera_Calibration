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
  <img src="https://github.com/joyuns/Camera_Calibration/assets/90548771/dae12bcd-cb55-4ae0-8c48-55b5ae7d6d2c">
</p>
-카메라 캘리브레이션 결과<br/>
<p align="center">
  <img src="https://github.com/joyuns/Camera_Calibration/assets/90548771/3626b58c-0bfc-4f98-a1b5-bce42cef9f61">
</p>
-왜곡 보정 전<br/>
<p align="center">
  <img src="https://github.com/joyuns/Camera_Calibration/assets/90548771/e5c260a0-60cb-4cbe-9196-6052b32ccdf4">
</p>
-왜곡 보정 결과<br/>
<p align="center">
  <img src="https://github.com/joyuns/Camera_Calibration/assets/90548771/093795cb-c1b6-4b4f-b795-efbcf40d96b4">
</p>
<p align="center">
  <img src="https://github.com/joyuns/Camera_Calibration/assets/90548771/376470a5-cdb8-4162-9f54-71285fc6d532">
</p>
