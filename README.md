# SL Project 

A **Sign Language to Text and Speech Conversion System** built using **OpenCV, Mediapipe, and Machine Learning**.  
This project aims to bridge the communication gap between the hearing-impaired community and others by translating sign language gestures into text and speech in real time.

---

## 🚀 Features
- 📷 **Real-time Hand Gesture Detection** using OpenCV and Mediapipe  
- 🔤 **Alphabet & Gesture Recognition** with a trained ML model  
- 🔊 **Text-to-Speech Conversion** for predicted characters/words  
- 📝 **Live Text Display** of recognized signs  
- 🎯 Easy-to-use interface and lightweight implementation  

---

## 🛠️ Tech Stack
- **Python**  
- **OpenCV** – for video capture & image processing  
- **Mediapipe** – for hand landmark detection  
- **Scikit-learn / TensorFlow / Keras** – for ML model training  
- **pyttsx3 / gTTS** – for text-to-speech  

---

## 📂 Project Structure
SL-Project/
│-- data/ # Collected dataset of gestures
│-- models/ # Trained ML models
│-- main.py # Main script for real-time inference
│-- inference_classifier.py # Gesture recognition module
│-- requirements.txt # Dependencies
│-- README.md # Project documentation

---


---

## ⚙️ Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/<Sanchay-3011>/SL-Project.git
cd SL-Project
pip install -r requirements.txt
python main.py
```

---

📊 Dataset

Custom dataset collected using hand gestures captured via webcam.

Includes A–Z alphabets and basic signs.

---

🤝 Contributing

Pull requests are welcome! If you’d like to contribute, please fork the repo and submit a PR.

📜 License

This project is licensed under the MIT License.

👩‍💻 Author

Sanchay Roy – https://github.com/Sanchay-3011
