# My personal project 

Implementation of paper - [YOLOv7: Trainable bag-of-freebies sets new state-of-the-art for real-time object detectors](https://arxiv.org/abs/2207.02696)

Re-implementation - [WongKinYiu/yolov7](https://github.com/WongKinYiu/yolov76)



## Dataset 

- I used a dataset from roboflow(https://universe.roboflow.com/mohamed-traore-2ekkp/face-detection-mik1i)

## Fine tuning 
- I have fine tuned face detetection model using pretrained model
- There is a pretrained model in the directory "pretrained"
- There is a fine tuning model I have done in the directory "finetuning" 
- coda : python detect.py --weights finetuning/face_detection.pt --conf 0.7 --img-size 640 --source attendance_test.mp4


## Inference : face detection

- I used a video clip of Korean dramas.
- The result of my fine tuning is in the directory "runs/detect/exp8"


## Notice
- The experiences I have carried out will be described in detail later.
