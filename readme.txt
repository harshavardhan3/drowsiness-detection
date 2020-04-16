This project to run needs a trained model for predicting shape of eyes which is in a file>50 mb so
given below is a drive link to download the file.

https://drive.google.com/open?id=1fVzuf1zJ-3mLwTHNQwr98tvK1xJs183b

download all the files in a folder and run the code below
$ python drowsiness_detection.py -p shape_predictor_68_face_landmarks.dat -a alarm.wav

The above implements using default camera on computer.

For a usb webcam,
$ python drowsiness_detection.py -p shape_predictor_68_face_landmarks.dat -a alarm.wav -w (index of webcam as a integer remove brackets)
