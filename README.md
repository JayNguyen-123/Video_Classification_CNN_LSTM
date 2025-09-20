# Video_Classification_CNN_LSTM
A 3D-CNN-LSTM vision encoder is a deep learning model that processes video sequences by extracting spatial features (using 3D CNNs) and modeling temporal relationships across the spatial features using LSTMs. This is commonly used in action recognition and video classification tasks.

This architecture consists of:

1. 3D convolutional layers (extract spatial features from video frames).

2. Flattening and temporal processing with LSTM (model sequential relationships across the video frames).

3. Fully connected layers for video classification.

- The dataset for training is a small, light weight Kinetic400-tiny for our small project.
- Class 0 is a demonstration of rope climbing, while class 1 is a demonstration of welding.
