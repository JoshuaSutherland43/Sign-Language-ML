# 🤟 Sign Language Gesture Recognition using MediaPipe & Machine Learning

This project is a **real-time hand gesture recognition system** that utilizes **MediaPipe** and custom machine learning models to identify and interpret **sign language gestures**, including static signs, pointing gestures, and motion-based gestures.

Built upon [Kazuhito00's base code](https://github.com/Kazuhito00/), this system combines the power of **MediaPipe for hand tracking** with **TensorFlow-based models** trained in **Jupyter Notebook** environments to recognize and output gesture-based communication.

---

## ✨ Features

- 🖐 **Hand Landmark Detection**  
  Uses **MediaPipe** for accurate real-time hand tracking and keypoint extraction.

- 📊 **Gesture Classification**  
  Custom machine learning models classify hand gestures using normalized keypoint data.

- 🔁 **Support for Motion Gestures**  
  Includes tracking of point history to interpret dynamic gestures, not just static signs.

- 🔡 **Text Output System (Planned)**  
  Future implementation will convert gestures into corresponding text for communication.

- 🔊 **Text-to-Speech (Planned)**  
  Plans to add audio feedback for recognized gestures using a text-to-speech model.

- 🌐 **Extensible Framework**  
  Easy to integrate with mobile or web-based applications using modular Python code.

- 📷 **Live Webcam Integration**  
  Capture and analyze hand gestures directly from your webcam using OpenCV.

---

## 🧠 Technologies Used

- **MediaPipe** – For real-time hand and finger tracking  
- **TensorFlow** – Model training and gesture classification  
- **Jupyter Notebook** – Interactive training and data visualization  
- **OpenCV** – For capturing webcam input and drawing visual outputs  
- **Python** – Core programming language for development  
- **NumPy & Pandas** – Data processing and manipulation  
- **Matplotlib** – Visualizing training data and model performance

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/sign-language-gesture-recognition.git
   cd sign-language-gesture-recognition
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the main program:
   ```bash
   python main.py
   ```

4. To train your own model, explore the Jupyter Notebooks in the `/notebook/` directory.

---

## 📈 Future Plans

- 🔤 Expand sign language vocabulary coverage
- 📝 Implement text generation from gesture sequences
- 🔊 Add a TTS (Text-to-Speech) system for vocalizing recognized gestures
- 📱 Explore deployment to mobile platforms for on-the-go accessibility
- 🧪 Add more gesture data collection tools for custom dataset creation
- 💡 Implement user profiles to save custom gestures and preferences

---

## 📷 Sample Output

Screenshots and videos of the system in action will be uploaded to demonstrate gesture tracking and recognition in real time.

![Screenshot 2025-05-26 222602](https://github.com/user-attachments/assets/575e85cd-73d8-4570-97e0-65b65edd2ff4)


---

## 🤝 Acknowledgements

- [Kazuhito00](https://github.com/Kazuhito00) – For the excellent base code and gesture recognition pipeline
- [MediaPipe by Google](https://mediapipe.dev/) – For real-time cross-platform hand tracking
- OpenCV, TensorFlow, and the open-source ML community

---

## 📬 Contact

For questions, collaboration, or feedback, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/joshua-sutherland/) or open an issue on this repo!

---
