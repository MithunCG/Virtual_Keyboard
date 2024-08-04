**Virtual Keyboard**
A simple virtual keyboard created using OpenCV and Python which has 26 alphabets, numbers, enter, a backspace and a space bar.

Our project implements a virtual keyboard interface utilizing hand tracking technology via 
OpenCV and the CVZone library. The system captures video input from a webcam and employs a hand 
detection algorithm to identify and track hand landmarks. A predefined layout of keyboard keys is 
represented as interactive buttons on the screen. The application detects user interactions through the 
index finger's position and the proximity of the thumb to simulate key presses. Specific gestures, such 
as hovering over a key with the index finger and pinching with the thumb, trigger corresponding 
keyboard actions. The virtual keyboard supports standard keys, along with special functions like space, 
enter, and backspace. This innovative approach provides a hands-free typing experience, enhancing 
accessibility and user interaction with digital devices.

The main purpose of this project is to use computer vision techniques (OpenCV and the 
cvzone library) and input simulation to create a hands-free interaction. The project uses a 
webcam to recognize hand gestures and simulates key presses that correspond with the virtual 
keyboard button when certain gestures are detected. It presents a visual mock-up of the virtual 
keyboard on the screen with buttons that change one evident attribute (font colour) depending 
on whether they have been hovered over or pressed. The project demonstrates composite use 
of many Python libraries (cv2, cvzone, numpy, pynput) and converges into one solution for 
virtual interaction.
