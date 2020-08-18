# Attendance-System-Project
Project is to build a face recognition-based attendance monitoring system for Companies/Schools/Colleges etc.

In this project, face databases will be created to pump data into the recognizer algorithm. Then, during the attendance taking session, faces will be compared against the database to seek for identity.


When a person is identified, their presence will necessarily be taken down, saving them in an Excel sheet with the date and time. At the end of the day, attendance information about a person can be accessed from an Excel file.


Working 

When we run attendance.py file, A GUI will be opened asking to Enter Id and Enter Name. After enter name and id then we have to click on Take Images button. 

By clicking Take Images camera of running computer is opened and it start taking image sample of person. This Id and Name will be stored in folder Employee Details and file name is Employee_Details.csv. 

It takes 80 images as sample and store them in Training Image folder. After completion of face detection, it will notify that images are taken and saved. After taking image samples, we have to click Train Image button. 

Now it take few seconds to train machine for the images that are taken by clicking Take Image button and creates a Trainer.yml file and store in Trainer folder. 

Now all initial setups are done. By Clicking on Take Attendance camera of running machine will be opened again. If face is recognized by system then Id and Name of person is shown on Image and the remarks section. Press Q(or q) for close this window. 

After closing it attendance of person will be stored in Attendance folder as csv file format with name, id, date and time.
