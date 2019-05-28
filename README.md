# Switching Different Resolution of Real-time Detection within implemented PyTorch of YOLOV3 

This final project for earning my Master's degree. Copyrights reserved. If you are interested my work, please cite it. 
As for the pre-request, please refer the other [Pytorch repo](https://github.com/ayooshkathuria/pytorch-yolo-v3) 
```
@book{Video Analytic with Dynamic Resolution,
    Author = {Di An},
    Year = {2019}
}

```


### On Video
For this, you should run the file, video_demo.py with --video flag specifying the video file. The video file should be in .mp4 format
since openCV only accepts OpenCV as the input format. 

```
python3 video_demo.py --video video.mp4
```

### On a Camera
Same as video module, but you don't have to specify the video file since feed will be taken from your camera. To be precise, 
feed will be taken from what the OpenCV, recognises as camera 0. The default image resolution is 160 here, though you can change it with `reso` flag.




