# Color Detection Using KNN Classifier

Color detection involves identifying and categorizing colors within digital images or video streams. It plays a vital role in image processing and computer vision, aiding tasks like object recognition and scene analysis. Utilizing algorithms to analyze color information contributes to diverse applications in fields such as robotics, augmented reality, and consumer electronics, enhancing functionality and user experience.

## Dependencies

To run the scripts in this repository, the following libraries are required:
- numpy
- opencv2
- math
- sys
- operator

## Features
- **KNN Classifier:** Utilizes the KNN algorithm to classify colors based on their pixel values.
- **Training Data:** The training data is created using folders dedicated to different colors.
- **Accuracy:** Achieves high accuracy in color detection, making it suitable for various applications such as image processing and analysis.

## KNN Classifier
K-Nearest Neighbors (KNN) is a simple yet powerful supervised learning algorithm used for classification and regression tasks. It assigns labels or predicts values based on the majority vote or average of the k nearest data points in the feature space. The new test data point is assigned to a particular color group using the Euclidean distance between RGB values.

## Usage
1. Install dependencies using the provided requirements file.
2. Run the color detection script, providing input images for analysis.
3. View the output results, including color classification and pixel segmentation.

## Feature Extraction 
Color Histogram is a representation of the distribution of colors in an image. For digital images, a color histogram represents the number of pixels that have colors in each of a fixed list of color ranges, that span the image's color space, the set of all possible colors.

![Screenshot 2024-04-08 204704](https://github.com/ShasankKasi/Color-Detection/assets/113813427/d54ab1a2-eed4-4317-bceb-ffdd4a7674a0)

## Implementation 
The provided Python script is a comprehensive implementation for real-time color detection utilizing the OpenCV library.The script integrates color histogram feature extraction and k-nearest neighbors (KNN) classification techniques. It captures frames from a
connected webcam, performing color histogram feature extraction on each frame. The
extracted features are then utilized by the KNN classifier to predict the color of objects within the frame. The script dynamically checks for the existence of training data,
automatically generating it if absent.
![Screenshot 2024-04-08 200327](https://github.com/ShasankKasi/Color-Detection/assets/113813427/2c708a5c-8e55-4adc-8343-0f598f6e5f72)


## Testing Data
The provided ‘color classification webcam.py‘ script begins by verifying the existence
of training data. If absent, it triggers the creation of training data by invoking
color histogram extraction.py‘. Subsequently, the script initializes the webcam to capture live frames and calculates the color histograms using ‘color histogram of test image.py‘
to extract BGR values. These values are then passed to the KNN classifier for color prediction. Finally, the predicted color is displayed on the webcam feed. 

![Screenshot 2024-04-08 194056](https://github.com/ShasankKasi/Color-Detection/assets/113813427/9fa7e960-ea18-47fb-91b2-09714d944e03)

## Color Detection Demo Video

Watch a demo video showcasing color detection using the KNN classifier:


https://github.com/ShasankKasi/Color-Detection/assets/113813427/93908ccd-b80f-40db-b1e0-2a902a1274ae



Click the image above to play the video.

## Conclusion

Thank you for exploring our Color Detection project using the KNN classifier! In this project, we demonstrated how the KNN algorithm can accurately classify colors based on pixel values, contributing to various applications in image processing and analysis.
