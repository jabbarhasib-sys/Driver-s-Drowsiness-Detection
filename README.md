# Driver-s-Drowsiness-Detection
😴 Driver Drowsiness Detection using CNN
📌 Overview

Driver drowsiness is one of the major causes of road accidents.
This project implements a Driver Drowsiness Detection System using Convolutional Neural Networks (CNN) to classify whether a driver is drowsy or alert based on facial features captured through a camera.

The system processes real-time video frames, detects the driver’s face and eyes, and predicts drowsiness to help prevent accidents.

🎯 Objectives

Detect driver drowsiness using deep learning

Classify eye states as drowsy or non-drowsy

Provide real-time monitoring using webcam input

Improve road safety through early warning detection

🧠 Methodology

Capture video frames using a webcam

Detect face and eye regions using OpenCV

Preprocess images (grayscale, resizing, normalization)

Use a CNN model to classify drowsiness

Display prediction results in real time

🛠️ Technologies Used

Programming Language: Python

Libraries & Frameworks:

TensorFlow / Keras

OpenCV

NumPy

Matplotlib

Scikit-learn

📂 Project Structure
├── dataset/               # Training and testing images
├── model/                 # Trained CNN model
├── src/
│   ├── train.py           # Model training
│   ├── detect.py          # Real-time detection
├── requirements.txt       # Required libraries
├── README.md              # Project documentation

⚙️ Installation

Clone the repository

git clone https://github.com/your-username/driver-drowsiness-detection.git


Navigate to the project directory

cd driver-drowsiness-detection


Install dependencies

pip install -r requirements.txt

▶️ How to Run
Train the Model
python train.py

Run Real-Time Drowsiness Detection
python detect.py


(Ensure your webcam is connected)

📊 Results

The CNN model achieved high accuracy on validation data

Successfully detects drowsy and alert states in real time

Efficient performance with minimal latency

🔮 Future Scope

Add audio alerts when drowsiness is detected

Improve accuracy using advanced CNN architectures

Deploy as a mobile or web-based application

Integrate with vehicle safety systems

🤝 Contributions

Contributions, issues, and feature requests are welcome!
Feel free to fork this repository and submit a pull request.

📜 License

This project is licensed under the MIT License.

👤 Author

Jabbar Hasib
