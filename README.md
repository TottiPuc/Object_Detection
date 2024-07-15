# Object_Detection


In this repository, we will install and run YOLO v3 using the latest libraries of OpenCV and Python 3.9 in Ubuntu

Requirements

You require the following hardware to be able to run the scripts.


* Intel i3 CPU or higher
* 4GB of DDR3 RAM or higher
* NVIDIA Graphics Card with 4GB RAM or higher with CUDA supported
* Hard drive - 256 GB or larger
* Webcam
* Android Device

## Step 1.

You need to install Anaconda and run the following line of code to create a new environment with the specific libraries required to execute the project.

* conda create -n yolov31 python==3.9
* conda activate yolov31
* pip install -r requirements.txt

## Step 2.

* Clone YOLO v3 repo
  - git clone https://github.com/ayooshkathuria/pytorch-yolo-v3.git (Original repo works with python3.6)
  - git clone https://github.com/TottiPuc/Object_Detection.git (Repo with some changes to work on python3.9)
    
* Download the weights
  - wget https://pjreddie.com/media/files/yolov3.weights

## Step 3.

  * Download a video (.mp4/.avi)
  * Run demo on video
    - python video_demo.py --video video.mp4
  * Run demo on webcam
    - python cam_demo.py
  
