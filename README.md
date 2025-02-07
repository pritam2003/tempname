# 🤟 Sign Language Recognition

Real-time sign language recognition using computer vision and deep learning.

## 📋 Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## 🔧 Prerequisites
- Python 3.8+ [I am using 3.10.11 But I installed 3.12.8 on my laptop and it still worked.]
- Webcam for real-time recognition
- pip (Python package manager)

## 📦 Dependencies
The following Python packages will be automatically installed:
| Package | Description |
|---------|-------------|
| TensorFlow | Machine learning framework |
| OpenCV | Computer vision library |
| MediaPipe | Hand tracking and pose estimation |
| scikit-learn | Machine learning utilities |
| matplotlib | Data visualization |
| numpy | Numerical computing |

## 💻 Installation

### 1. Clone the Repository

2. Create and activate a virtual environment 

3. Install dependencies
    pip install -r requirements.txt

## 🚀 Usage

### 1. Activate Virtual Environment

### 2. Run the Program

### 3. Controls
- Press 'q' to quit the webcam window
- Use Ctrl+C in the terminal to stop the program

> **Note:** Ensure your webcam is connected and accessible before running the program.

## Folder Structure

sign_language_detection/
│
├── data/                   # Collected keypoint sequences
├── models/                 # Saved LSTM models
│
├── utils/                  # Helper functions
│   ├── mediapipe_utils.py  # MediaPipe detection/rendering
│   ├── data_utils.py       # Keypoint extraction
│   └── model_utils.py      # LSTM model builder
│
├── collect_data.py         # Data collection script
├── train.py                # Model training script
├── detect.py               # Real-time detection script
├── test_webcam.py          # Webcam test script
└── requirements.txt        # Dependencies

## 👥 Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing_feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing_feature`)
5. Open a Pull Request

## License


