📌 Overview
This project implements real-time face detection using OpenCV and the Haar Cascade Classifier.
It uses a webcam feed to detect human faces and draws a bounding rectangle around them.

📂 Project Structure

├── FaceDetetctionCode.txt            # Main Python script for face detection

├── haarcascade_frontalface_default.xml  # Pre-trained Haar Cascade model


⚙️ Requirements
Python 3.x

OpenCV library

Install OpenCV using:

pip install opencv-python


🚀 How to Run
Clone the repository:

git clone https://github.com/yourusername/face-detection-opencv.git
cd face-detection-opencv
Make sure the haarcascade_frontalface_default.xml file is in the same directory as the script.

Run the script:

python FaceDetetctionCode.txt
A window will open showing the webcam feed with detected faces highlighted.

Press Q to quit.

🛠 How It Works
Load Haar Cascade Model – The script loads the pre-trained Haar Cascade classifier for frontal face detection.

Capture Video Stream – The webcam feed is read frame by frame.

Convert to Grayscale – The captured frame is converted to grayscale for processing efficiency.

Detect Faces – detectMultiScale() identifies faces in the frame.

Draw Bounding Boxes – Detected faces are marked with green rectangles.

📸 Example Output
When running, the output will look similar to this:

[ Webcam feed showing faces with green rectangles ]

Copy
Edit
[ Webcam feed showing faces with green rectangles ]
