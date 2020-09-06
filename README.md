# How to use this project-
open command prompt and type python gender_age1.jpg if you want to predict your age and gender using your webcam and type python gender_age1.jpg -i 'image path' if you want to predict using any image and press enter.

# About the files of the project-
sample images-
1.jpg
2.jpg
3.jpg

Face prototype and model used-

1.opencv_face_detector.pbtxt

2.opencv_face_detector_uint8.pb

Age prototype and model used-

1.age_deploy.prototxt

2.age_net.caffemodel

Gender prototype and model used-

1.gender_deploy.prototxt

2.gender_net.caffemodel

Main project file is the "gender_age1.py".

# About this project-
With this model we can predict the gender and age of the person by detecting the face in the image or by the webcam live image.

# libraries used-
In this particular project inhave used many libraries and models which are pre-trained. I have used opencv-python , math , time , argparse to pass the argument at the runtime of the project.In this model the prototext and models of face,gender and age is used which are commonly known as caffe model in deep neural network.

# output-
The output of this project is either we can use the webcam or video source for capturing the video or we can use the existing image through the argument parser.
The output is according to the face of the person showing the age and gender and the percentage of the confidence with the model is predicted.
There is the rectangle on the face above which the age and the gender of the person is mentioned.

# Thankyou
