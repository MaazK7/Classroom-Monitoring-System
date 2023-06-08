# Classroom-Monitoring-System
This system records attendance along with their expression, apart from that it also counts the number of students present in frame using computer vision techniques.
Following are the steps to implement this system:
1. Generate Encodings
  - Create a Folder under the Faces folder with the name of the person. Add atleast 5-10 pictures in that folder.
  - Run the train_v2.py 
  - After running it will generate a encodings.pkl file in the encodings folder.
  - Make sure the encodings are generated
2. Attendance Module
  - Copy the encodings.pkl file in the encodings folder of Attendance Module
  - Now you are good to go and run the main file.

3. Rest of files were used for training the FER Module
