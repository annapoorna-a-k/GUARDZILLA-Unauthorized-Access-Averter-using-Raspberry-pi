<h2>Guardzilla: Unauthorized Access Averter using RaspberryPi</h2>
<h3>Introduction</h3>
Guardzilla is a state-of-the-art intrusion entry detection robot that patrols your premises. It is built on the concept of face detection using OpenCV. It has live-feed camera access through which the owner can access the surveillance system.
<p>It's also a creative and innovative piece of technology pushing the boundaries of what's possible. With Guardzilla, you can rest assured that your premises are protected.</p>

## <h3>Project Overview</h3>
The robot uses OpenCV for real-time face detection and sends email alerts whenever an intruder is detected. These alerts include attached images of the detected faces for user verification. Furthermore, the system offers live video streaming via a Flask web server, enabling users to monitor their environment remotely.

The robot's movements can be controlled remotely through a web interface that can be accessed from a mobile device, increasing its versatility and ease of use.

This system is designed to be effective, user-friendly, and affordable, making home security more accessible for everyone.

## <h3>Functionalities</h3>
<ul>
  <li>Real-time Face Detection: The system uses OpenCV to detect faces in real time. Any detected faces are treated as intruders, triggering the system's alert mechanisms.

</li>
  <li>Email Alerts: When an intruder is detected, the system sends an email alert to the user. This email includes an image of the intruder's face for verification.

</li>
  <li>Live Video Streaming: Users can monitor their environment in real time through the system's video stream. This stream is accessible through any web browser, enabling remote surveillance.

</li>
  <li>Remote Control: The robot's movements can be controlled remotely through a web interface. This interface is designed to be user-friendly and can be accessed from any mobile device.

</li>
 
</ul>

## <h3>Components</h3>
<ul>
  <li>Motor Driver (Version L2981)</li>
  <li>Raspberry Pi (Version: 4)</li>
  <li>USB Webcam</li>
  <li>GPIO Buzzer</li>
  <li>Chassis or Robot Body</li>
  <li>Power Bank or Battery</li>
  <li>Jumper Wires</li>
  <li>SD Card</li>
</ul>

## <h3>Installation</h3>
1. On your Raspberry Pi, with Raspberry Pi OS, Install the Required Python Libraries and Other Dependencies.<br>
```
pip install flask opencv-python gpiozero numpy imutils
sudo apt-get install libncurses5-dev libncursesw5-dev```
```
2. Git Clone this repository
Make necessary changes in the code of "integrate.py", such as the sender's email-id, password and receiver's email id to the owner's mail id.
```
git clone https://github.com/annapoorna-a-k/GUARDZILLA-Unauthorized-Access-Averter-using-Raspberry-pi/
```
3. Run the application. You can run the 3 Python codes in three different terminals to access all functionalities at the same time.
```
python integrate.py
python move.py
python phonemove.py
```
4. Access the live video feed and control interface through your web browser. If your Raspberry Pi and your computer are on the same network, just navigate to `http://<RaspberryPi_IP>:5000/`  for the live video feed and `http://<RaspberryPi_IP>:5005/`  for the control interface (replace <RaspberryPi_IP> with the actual IP address of your Raspberry Pi).

## <h3>Flowchart</h3>
![robo](https://github.com/annapoorna-a-k/Guardzilla_Unauthorized-Access-Averter/assets/98168268/551c0c50-6391-48b1-a687-1a206cfa2b81)

## <h3>More Images of the Robot</h3>


<img width="123" alt="IMG20230722220403-removebg-preview-removebg-preview" src="https://github.com/annapoorna-a-k/Guardzilla_Unauthorized-Access-Averter/assets/98168268/59819453-d3ba-47c6-8725-eb1ee305eb3b">
&nbsp; &nbsp;
&nbsp;

<img width="135" alt="IMG20230722220620-removebg-preview-removebg-preview" src="https://github.com/annapoorna-a-k/Guardzilla_Unauthorized-Access-Averter/assets/98168268/8f18702f-891c-460f-8c7e-c8ab20aeea94">

