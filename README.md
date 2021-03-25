# Smartdoor Lock System using Fingerprint and Camera 

By this project we can do Smartdoor Lock System using Fingerprint and Camera to increase the security of home, Office and etc. In this project we will check the fingerprint using sensor and face using webcam if match then Unlock otherwise not.

**Hardware requirements:**
- Arduino Uno.
- Fingerprint Sensor.
- solenoid lock.
- Relay.
- wires as per your requirements. 
- 12v Adapter.

**Software requirements:**
- Arduino IDE.
- arduino Library - Adafruit-Fingerprint-Sensor-Library (uploaded into this folder)
- pycharm or any prefered Python IDE.
- python Libraries : face_recognition, cv2, serial, numpy

As mentioned we can do Door lock/unlock using 2 ways : <br>
1. Using **Fingerprint**
2. Using **Face Recognition**

After downloading this project follow the following steps :
1. **Fingerprint**
    1. First make connection like shown in the below figure
        ![](https://github.com/Rushit2907/Smartdoor-Lock-System-using-Fingerprint-and-Camera/blob/main/Pin%20Diagram.jpg)
    2. Now we need to enrol the figerprint in fingerprint sensor so using enroll.ino file upload the code into arduino and run.
    3. after enrolling the fingerprint use fingerprint_compare program and upload it into arduino uno and upload.
    4. now you can put the finger on the sensor and test it,

2. **Face Recognition**
    1. Same connection but without Fingerprint Sensor.
    2. In this part first you need an image of your face and put it in the same folder and change the path in the image variable.
    3. Now to check that Face Recognition python file is properly working or not, Comment 6,37 lines and Run and check face recognition is properly working or not.
    4. After checking this, upload serial_python file into arduino uno.
    5. Remove comment in python file and run python file and Run the Python Code.

## Demo:
#### Fingerprint
![](https://github.com/Rushit2907/Smartdoor-Lock-System-using-Fingerprint-and-Camera/blob/main/demo1.gif)

#### Face Recognition
![](https://github.com/Rushit2907/Smartdoor-Lock-System-using-Fingerprint-and-Camera/blob/main/demo2.gif)

## Facing any issues?

Feel free to [open an issue](https://github.com/Rushit2907/Smartdoor-Lock-System-using-Fingerprint-and-Camera/issues/new). We are glad to help you. And is you have solution for that issue I will allocate to you. ❤️ 

If you have any more idea related to this project then please share your idea on rushitajudiya2907@gmail.com. If time permits I will surely do some work on your project.

