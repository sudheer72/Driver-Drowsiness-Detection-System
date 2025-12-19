# Driver Drowsiness Detection System Using Computer Vision

## 📌 Overview
This project is a real-time driver drowsiness detection system designed to enhance road safety by monitoring a driver’s alertness using computer vision techniques. The system continuously analyzes facial features such as eye closure and yawning patterns to detect signs of fatigue and triggers alerts to prevent potential accidents.

The solution runs locally on a standard CPU without requiring internet connectivity, making it suitable for real-world deployment in vehicles.

---

## ✨ Features
- Real-time face detection and tracking
- Eye Aspect Ratio (EAR) based blink detection
- Yawning detection to identify fatigue
- Continuous monitoring of driver alertness
- Audio/visual alerts when drowsiness is detected
- Lightweight and efficient CPU-based execution

---

## 🛠️ Technologies Used
- Python  
- OpenCV  
- Dlib  
- Facial Landmark Detection (68-point model)  

---

## ▶️ How It Works
1. The camera captures live video of the driver.
2. Dlib detects facial landmarks from the driver’s face.
3. Eye landmarks are used to calculate the Eye Aspect Ratio (EAR).
4. Prolonged eye closure or frequent yawning indicates drowsiness.
5. When fatigue thresholds are exceeded, the system triggers alerts.
6. Alerts notify the driver to regain focus or take a break.

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/driver-drowsiness-detection.git
````

2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Python script:

   ```bash
   python drowsiness_detection.py
   ```

---

## 📊 Performance

* Real-time detection with minimal latency
* Reliable performance under moderate lighting conditions
* Works effectively on CPU-only systems
* Capable of detecting fatigue within a few seconds of onset

---

## 🎯 Use Case

* Prevents road accidents caused by driver fatigue
* Can be integrated into vehicle safety systems
* Useful for long-distance drivers and night driving scenarios
* Enhances overall road safety through early alerts

---

## 🚀 Future Enhancements

* Integration with vehicle control systems
* Support for mobile or embedded devices
* Improved accuracy under low-light conditions
* Machine learning-based fatigue prediction models

---

## 👨‍💻 Author

**Sudheer Ravi**
B.Tech – Computer Science and Engineering
VIT-AP University
