# HDRplus
HDRplus is a cutting edge handwriting recognition application.
Currently it only supports recognition of handwritten digits.
This is because the Neural Network is currently only trained using handwritten digits data-set as of now.

The applciation works as follows:
The image is first clicked using an Android app(front-end).
The image is then pre-processed to segment, enhance, crop, binarize and resize the image(pre-processing).
The application has a neural network processing engine that perfroms the major identification of a character from the image(processing).
The output is combined with previously recognized data and sent back to the android app UI using a RESTful Web service(web-service).

Currently we are able to obtain a recognition at an average accuracy of 90% provided the Android phone camera is not of a very poor quality.

Minimum Android version - Android 4.0

Efforts are constantly being made by the team to improve upon the application. We hope you like it! :)
