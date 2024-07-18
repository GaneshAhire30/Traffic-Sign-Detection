# Traffic-Sign-Detection
# AI PROJECT ON GERMAN TRAFFIC SIGN DETECTION :-
#  BUSINESS CASE:- Based on the image data we need to predict the traffic sign detection.
## DATA COLLECTION :-
* Data Collected form Rubixe For Educational Internship.

# TASK: Object Detection :-

## DATA INFORMATION :-
* Total 9030 traffic sign images are present in 43 classes Each class contain     210 images
* Split data with the help of splitfolder library.
* 189 Images for training and 21 images for validation
* Create bounding boxes with the help of label-img tool and makesense.ai         website

![image](https://github.com/user-attachments/assets/482e1ac6-41c3-4e03-b8f6-571b03e37240)

## DATA PREPRATION :-
* Prepare folder structure that can be accept by YoloV5.
* Total 8127 images for training and 903 images for validation present in 43     classes.
* Create a bounding boxes with the help of label-img And makesense.ai website     according to YoloV5.

 ## STEPS TO USE YOLOV5 :-
* Cloning the YoloV5 file from official repository.
* Changing the directory of yolov5
* Installing the dependencies
* Download all versions pre-trained weights

## STEPS BEFORE TRAINING CUSTOM DATASET :-
1. Go to yolov5/data/

2. Open coco128.yaml

3. Edit the following inside it:

   A. Training and Validation file path

   B. Number of classes and Class names.

## TRAINING YOLOV5 MODEL :-
* Set images size 128 with batch of 8
* Train model on 100 epochs
* Gives the data file path as well as give pre-trained weights path.

## AFTER TRAINING THE MODEL :-

### VISUALISE THE TRAINING METRICS WITH THE HELP OF TENSORBOARD

![image](https://github.com/user-attachments/assets/549d0f82-8708-4e33-8b16-fb8d90fdc885)

# PREDICTED IMAGES:

![image](https://github.com/user-attachments/assets/8a6b336d-0e2e-4665-ab78-1e7ce58e41ff)

![image](https://github.com/user-attachments/assets/36433c0d-b9fd-477a-af47-a88743bf8901)

![image](https://github.com/user-attachments/assets/7760761c-60c3-49f9-9981-add5b7e92b80)

![image](https://github.com/user-attachments/assets/4089a107-8de6-4c62-9679-e1f14bb7e9f8)

![image](https://github.com/user-attachments/assets/6ec67dce-5448-4e02-a4a9-556f1eee5bcf)

# CHALLENGES FACED :-
* Facing problem to understand the business case.
* challenge faced in bounding boxes creation
* Assign same no for all classes
* Made mistake in yolov5 folder structure
* Take lots of time to create bounding boxes

# WHAT WE LEARN :-
* Convert classification task to object detection to improve skill in object     detection
* Understand the YoloV5 folder structure as well as learn label-img tool.
* Learn pytorch library.  
