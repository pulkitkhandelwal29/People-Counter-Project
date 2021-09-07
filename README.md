# People Counter Project
The project helps in measuring the number of people traversing a certain passage or entrance.

## Installation
1. Clone the repository and change the working directory to Project folder<br>
`git clone https://github.com/pulkitkhandelwal29/People-Counter-Project.git`

2. Create a virtual environment inside the project folder<br>
`virtualenv myenv`

3. Activate virtual environment <br>
`myenv\Scripts\Activate`

4. Install `dlib` using binary file in environment <br>
`python -m pip install dlib-19.19.0-cp38-cp38-win_amd64.whl`

5. Install the necessary packages in environment <br>
`pip install -r requirements.txt`

## Run the project
`python people_counter.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt --model mobilenet_ssd/MobileNetSSD_deploy.caffemodel --input videos/sample.mp4`

## Libraries
* OpenCV - Standard computer vision/Image processing functions
* Dlib - Implementation of correlation filters / correlation tracker implementation
* Imutils - OpenCV convenience functions
* Numpy - Comprehensive Mathematical Functions

## Trackers 
* Centroid Tracker
* Trackable Object

## Pre-trained Caffe Deep Learnign Models
* MobileNet SSD (Single Shot Detector)

