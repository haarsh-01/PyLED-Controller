**LED Control with Hand Gestures using Python**
This project demonstrates controlling LEDs using hand gestures detected via a webcam. The system uses Python and libraries like OpenCV, cvzone, and pyFirmata to capture hand gestures and translate them into LED control commands.
**Features**
1.)Hand Gesture Recognition: Uses a webcam to detect the number of fingers held up using the cvzone library's HandTrackingModule.
2.)LED Control: Controls LEDs connected to an Arduino via the pyFirmata library. Each detected hand gesture corresponds to a different LED lighting pattern.
3.)Real-Time Display: The current hand gesture (number of fingers held up) is displayed on the video feed in real time.

**How It Works**
The program uses a webcam to capture live video.
The hand is detected, and the number of fingers held up is tracked.
Based on the number of fingers, the program sends signals to the Arduino to control the LEDs:
0 fingers: All LEDs off.
1 finger: LED 1 on.
2 fingers: LEDs 1 and 2 on.
3 fingers: LEDs 1, 2, and 3 on.
4 fingers: LEDs 1, 2, 3, and 4 on.
5 fingers: All LEDs on.
