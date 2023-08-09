# Visual-Speech-Recognition
Through a user-friendly GUI powered by Tkinter, users can effortlessly upload videos, visualize real-time lip reading predictions, and explore the intriguing synergy between deep learning and computer vision. The project's core architecture, utilizing 3D convolutional neural networks and recurrent layers, adeptly captures spatial and temporal features, enabling the Bidirectional Gated Recurrent Units to decode intricate lip movements.The project provides an accessible platform for users to witness the captivating process of deciphering spoken content from visual cues. 
The system uses the Tkinter GUI library and OpenCV to provide an interactive interface for predicting and captioning lip movements in videos.

Key Features:

GUI Interface: A user-friendly GUI built with Tkinter allows users to upload and process videos for lip reading analysis.

Real-time Video Capture: Utilizing OpenCV, the project supports real-time video capture from a webcam or uploaded video source.

Video Captioning: A deep learning model (Key components - 3D convolutional layers, Bidirectional GRU, TimeDistributed and Dense Layer, Softmax Activation, CTC Loss) , is employed to convert lip motion patterns into accurate textual transcripts.

Upload and Predict: Users can upload videos and obtain lip reading predictions with a single click.

Automatic Caption Display: The predicted captions are seamlessly displayed in the GUI interface.

Text Clearing: A 'Clear' button enables users to reset the displayed captions.

Key technologies

Python
Tkinter (GUI Library)
OpenCV (Computer Vision Library)
NumPy (Numerical Computing Library)
Keras (Deep Learning Framework)
TensorFlow (Deep Learning Framework)
CNNs, RNNs
