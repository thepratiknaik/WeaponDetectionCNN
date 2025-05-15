
# Real-Time Weapon Detection Using CNN-Based Model

This repository contains the complete implementation of a real-time weapon detection system using a custom-built Convolutional Neural Network (CNN) developed from scratch without pre-trained models. The system is capable of detecting weapons such as guns, pistols, knives, and grenades in real-time using a laptop webcam.

## 📌 Project Overview

- Detects four classes: `Gun`, `Pistol`, `Knife`, and `Grenade`
- Utilizes a YOLOv5-style annotated dataset
- Custom CNN architecture implemented using TensorFlow and Keras
- Real-time object detection with OpenCV
- No reliance on pre-trained models, designed for lightweight performance

## 🚀 Features

- Custom-built CNN for classification
- YOLOv5-format dataset support
- Live detection via webcam
- Visual overlays with OpenCV
- Terminal alerts for weapon classes

## 🧠 Model Architecture

- Multiple convolutional layers with ReLU activation
- MaxPooling and Dropout for regularization
- Fully connected dense layers ending with softmax output
- Trained using Adam optimizer and categorical crossentropy

## 🛠️ Technologies Used

- Python 3
- TensorFlow 2.x
- Keras
- OpenCV
- NumPy, Pandas, Matplotlib

## 📂 Project Structure

```
├── dataset/                    # Contains images and YOLOv5-format label files
├── model/                      # Saved model in .h5 format
├── Real-Time_Weapon_Detection.ipynb  # Jupyter notebook for training and live detection
├── README.md                   # Project documentation
```

## 🖥️ How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/thepratiknaik/WeaponDetectionCNN/tree/main
    cd real-time-weapon-detection-cnn
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook:
    ```bash
    jupyter notebook Real-Time_Weapon_Detection.ipynb
    ```

4. Ensure your webcam is connected and active during the live detection demo.

## 📈 Results

- Moderate classification accuracy
- Successful detection on live webcam feed with class labels
- Bounding boxes and terminal alerts enhance visibility

## 📌 Future Improvements

- Add bounding box regression to improve localization
- Expand and diversify the dataset
- Implement real-time alerts via messaging or API calls
- Optimize model for edge deployment (e.g., Raspberry Pi, Jetson Nano)

## 🧑‍💻 Author

**Pratik Naik**  
Graduate Student, MS in Computer Science  
Pace University, New York City Campus
