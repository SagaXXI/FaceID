<div align="center">
  <a href="https://github.com/SagaXXI/FaceID">
    <img src="Logo.png" alt="Logo" width="80" height="80">
  </a>
</div>

# This is the official implementation of

## A Real-Time Face Identification and Attendance System using Pre-Trained Face Recognition Model

The Face ID Attendance System is an application that allows to automate the attendance process using facial recognition technology. The system is designed to recognize the faces of students or employees and record their attendance automatically in a database.

The application uses OpenCV library to capture the video stream from a webcam and Face-Recognition library to recognize the faces of the users using a pre-trained deep learning model. The model is trained on a dataset of images that represent the faces of the students or employees.

Once the faces are recognized, the system compares them with the faces in the database and records the attendance of the users who are recognized.

This is an early version of a project. Owing to this reason, our database of faces is incomplete. Currently, it contains faces of 3 celebrities: Emily Blunt, Elon Musk and Margot Robbie.
That's why it will recognize only these faces, and won't recognize others. However, you can add your own image or image of any person you want, which will be discussed in a How To Use section.

# Libraries
1. Tensorflow
2. Numpy
3. OpenCV
4. Firebase-Admin
5. Pandas
6. Pickle


# How to use

## Installation
1.git clone from repository https://github.com/SagaXXI/FaceID
2. Install the required libraries. (Conda environment preferred). Using pip install -r requirements.txt
3. Open the project in a IDE with python support
4. Make sure you have a webcam connected, and run main.py file.


## Run
1. Run 'user_interface.py'
2. Click on the 'Run' button.
3. Select 'Webcam' fom the list and leave all fields blank.
4. Click on 'Mark Attendance' button.
5. Attendance sheet will be generated automatically with current date/time.

## Adding Images
1. Choose and image and dowload it in a png format.
2. Give it a unigque name that consist of only 6 images. Again, unique (this is important)
3. Move it in images folder in a project directory.
4. Run EncodeGenerator.py and then AddDataToDatabase.py. (In this order!)
5. (Optional) If you want to add student details, then make changes to data variable in AddDataToDatabase.py
6. You are good to go! Run main.py and enjoy!


## Contacts
Daryn Tazabek - [LinkedIn](https://www.linkedin.com/in/daryn-tazabek-409100241/) - [Gmail](daryntazabek791@gmail.com)


## License

The code is available under MIT License. Please read the license terms available at [[Link]](https://github.com/SagaXXI/FaceID/blob/master/LICENSE)

