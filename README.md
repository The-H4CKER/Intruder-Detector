# Intruder-Detector
This project uses a Raspberry Pi and mobile device to sound an alarm when a person is visible. 

## Requirements
Hardware needed for this project include:
- A full Raspberry Pi desktop setup with monitor, keyboard, mouse etc.
- A breadboard 
- 3 LEDs (green, yellow and red)
- 3 330Ω resistors
- A push to make switch
- A small loudspeaker
- 7 male to female jumper connectors (5 for components and 2 for power)
- 2 male to male jumper connectors/solid-core 22 AWG wire (for buzzer and button)
- An Android/iOS device

All software for the Raspberry Pi is avaliable here however to remotely access a mobile device's camera we will use a free open-source software called DroidCam by Dev47Apps. 
The download links for this are shown below:

Android: https://play.google.com/store/apps/details?id=com.dev47apps.droidcam

Apple: https://apps.apple.com/us/app/droidcam-webcam-obs-camera/id1510258102

## Usage

Install Raspberry Pi OS on a SD card and go through all the installation steps.

Installation is as follows:
```
pi@raspberrypi:~ $ git clone blah blah
pi@raspberrypi:~ $ cd Intruder-Detector/
pi@raspberrypi:~/Intruder-Detector $ chmod +x detector.sh 
pi@raspberrypi:~/Intruder-Detector $ ./detector.sh -i # Installs all dependencies for first-time usage
```
To start detection, simply run:
```
pi@raspberrypi:~/Intruder-Detector $ ./detector.sh
```

