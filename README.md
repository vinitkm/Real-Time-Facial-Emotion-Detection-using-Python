# Real-Time-Facial-Emotion-Detection-using-Python
Python libraries can analyze emotions in real-time by detecting facial expressions and displaying corresponding emoji emotions.

The program accesses the webcam and captures real-time video frames, which are then converted to grayscale. The Haar Cascade classifier is used to detect faces in the frames. Emotion analysis is performed on each detected face using DeepFace to extract the dominant emotion. The detected emotion is displayed as text above the face and an emoji is overlaid on the face if the corresponding emoji is available in the dictionary. The program runs continuously until the user presses the "Enter" key (keycode 13) or the "Esc" key (keycode 27), at which point the webcam is released and all OpenCV windows are closed.

The goal of this project is to provide users with a friendly and entertaining visual experience by overlaying emojis that represent the detected emotions on top of the detected faces. This approach is more effective than presenting emotions in a text format as pictorial representations tend to capture more attention. By watching their faces transform into emoji representations, users may gain insight into their own emotions, and society may benefit from this project.


#Please go through the repository 
#https://coderspacket.com/real-time-facial-emotion-detection

