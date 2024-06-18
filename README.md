# Visual-Based-Attendance

### steps to follow
- type `pip install -r requirements.txt` 
- open `attendance.py` and `automaticAttendance.py`
- Run `attandance.py` file

### Project flow & explaination
- After you run the project you have to register your face so that system can identify you, so click on register new student
- After you click a small window will pop up in that you have to enter you ID and name and then click on `Take Image` button
- After clicking `Take Image` button A camera window will pop up and it will detect your Face and take upto 50 Images and stored in the folder named `TrainingImage`. 
- Then you have to click on `Train Image` button, It will train the model and convert all the Image into numeric format so that computer can understand. we are training the image so that next time when we will show the same face to the computer it will easily identify the face.
- After training model click on `Automatic Attendance` ,you have to enter the subject name and then it can fill attendace by your face using our trained model.
- it will create `.csv` file for every subject you enter and seperate every `.csv` file accoriding the subject
- You can view the attendance after clicking `View Attendance` button. It will show record in tabular format.
