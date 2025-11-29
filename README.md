# Face based attendance system using Python and OpenCV

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)

### What steps you have to follow?
- Download or clone this repository to your device  
- Run `pip install -r requirements.txt` (this installs required packages)
- Create a `TrainingImage` folder inside the project directory
- Open `attendance.py` and `automaticAttendance.py`, then update all file paths according to your system
- Run the `attendance.py` file

---

### Project flow & explanation
- When you start the project, click **Register New Student** to register your face
- A window will open where you enter your **ID** and **Name**, then click **Take Image**
- The camera will capture up to **50 images** (you can change this number) and save them in the `TrainingImage` folder  
  More images = better model accuracy
- Click **Train Image** to train the model.  
  It converts the images into numeric format so the computer can recognize the face
- After training, click **Automatic Attendance**, enter the subject name, and the system will automatically mark attendance using your face
- The system creates a `.csv` file for every subject inside the project folder
- View attendance using the **View Attendance** button (shows data in a table format)

---

### Screenshots

#### Simple UI
<img src='https://github.com/Patelrahul4884/Attendance-Management-system-using-face-recognition/blob/master/Project%20Snap/1.PNG'>

#### While taking Image
![Screenshot (103)](https://user-images.githubusercontent.com/26384517/86820502-c7f44500-c0a6-11ea-9530-6317ec2059d9.png)

#### While taking Attendance
![Screenshot (91)](https://user-images.githubusercontent.com/26384517/86821090-9465ea80-c0a7-11ea-9680-777923663d0c.png)

#### Attendance in tabular format
<img src='https://github.com/Patelrahul4884/Attendance-Management-system-using-face-recognition/blob/master/Project%20Snap/7.PNG'>

---

## ⭐ If you find this useful, please give a star to the repository!
