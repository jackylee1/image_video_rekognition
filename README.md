# Objects Detection in uploaded Image/Video
Detects Objects in the Image(using AWS Rekognition API) and Video(using Clarifai API)

We need to upload an image/video file by going 127.0.0.1:8000/image or 127.0.0.1:8000/video urls respectively.
Python script written in Django views.py will upload it AWS or Clarifai and get the reponse and will show it at the frontend screen.

Image Upload Screen:
<p align="center">
  <img src="image_home.png" width=900 height=550>
</p>

Image Output Screen:
<p align="center">
  <img src="image_output.png" width=900 height=550>
</p>

Video Upload Screen:
<p align="center">
  <img src="video_home.png" width=900 height=550>
</p>

Video Output Screen:
<p align="center">
  <img src="video_output.png" width=900 height=550>
</p>

