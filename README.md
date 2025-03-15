### Overview

This is an Android application designed to help tourists identify unfamiliar objects by using real-time object detection and translation. The app utilizes YOLOv5, a state-of-the-art deep learning model, to recognize objects through the device’s camera, providing instant identification and translation into the user’s preferred language. Additionally, the app offers text-to-speech functionality to pronounce object names, enhancing accessibility for travelers.

### Development & Features

The project was developed using Python, Kotlin, and TensorFlow Lite, with a focus on efficient mobile inference to ensure fast and accurate results on Android devices. Key development milestones included:

- **Machine Learning Implementation**: Trained and optimized a YOLOv5 model for mobile use, with a dataset tailored for objects that tourists may encounter.
- **TensorFlow Lite Conversion:** Converted from PyTorch to TensorFlow Lite which had better support on Android.
- **Android Integration**: Developed an intuitive UI in **Android Studio**, implementing real-time camera processing and dynamic bounding box displays.
- **Multi-Language Support**: Integrated **on-device translation and text-to-speech** to allow seamless interaction without requiring an internet connection.
- **Performance Optimization**: Conducted extensive testing on TensorFlow Lite inference times, balancing model accuracy with real-time responsiveness.

### Development Screenshots

The following screenshots show development builds of the application.

![image](https://github.com/user-attachments/assets/0ba4ad90-f020-439e-9a71-63c1de6d507c)

*Testing the app on a photo of a bus.*

### Challenges & Learnings

The biggest challenge with this project was sourcing an appropriate dataset. Unfortunately, finding a dataset that included unique objects only found in certain countries turned out to be too difficult.
