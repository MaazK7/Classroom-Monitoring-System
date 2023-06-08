# Classroom-Monitoring-System
This system records attendance along with their expression, apart from that it also counts the number of students present in frame using computer vision techniques.
Following are the steps to implement this system:
1. Generate Encodings
  a) Create a Folder under the Faces folder with the name of the person. Add atleast 5-10 pictures in that folder.
  b) Run the train_v2.py 
  c) After running it will generate a encodings.pkl file in the encodings folder.
  d) Make sure the encodings are generated
2. Attendance Module
  a) Copy the encodings.pkl file in the encodings folder of Attendance Module
  b) Now you are good to go and run the main file.
