# FaceRecognition
FaceRecognition


Real-time face recognition project with OpenCV and Python

step:1 install the python in you pc/laptop.

step:2 simply install python libraries

		import face_recognition
		import cv2
		from openpyxl import Workbook
		import datetime

step:3 load the yours recognition image in set.

		# Load images.
  
		image_1 = face_recognition.load_image_file("demoFace/utsav.pgm")
		image_1_face_encoding = face_recognition.face_encodings(image_1)[0]
    
		image_2 = face_recognition.load_image_file("demoFace/5.pgm")
		image_2_face_encoding = face_recognition.face_encodings(image_2)[0]
		
step:4 simply run the python face_recog.py
