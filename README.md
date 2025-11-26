# 💻 Hand Gesture Controlled Automation Using (Machine Learning)

**Python + Machine Learning + MediaPipe Hands**

This project enables hands-free computer control using real-time hand gesture recognition. With a standard webcam, the system detects specific gestures (✌️ 👊 🖐️) and triggers automated actions such as opening or closing applications — no mouse or keyboard required.

**✋ Gesture Controls**
    Gesture	Action
    ✌️ Victory	Open Google Chrome
    👊 Fist	Open YouTube
    🖐️ Palm	Close Chrome

**Note: Each gesture is executed only once per detection cycle to prevent repeated triggers.**


**Output:**
<img width="1365" height="726" alt="Screenshot_1" src="https://github.com/user-attachments/assets/4c0f20d9-18c3-438d-bfda-ba9814abe364" />
<img width="1365" height="725" alt="Screenshot_2" src="https://github.com/user-attachments/assets/edc22bf2-27ed-43b4-8767-2700f9a682a6" />
<img width="1365" height="726" alt="Screenshot_3" src="https://github.com/user-attachments/assets/08d5d818-f216-491d-a7ed-14d24783cdda" />
<img width="1365" height="724" alt="Screenshot_4" src="https://github.com/user-attachments/assets/24d8e8fa-84d9-4ff0-9cc5-80b3554bf235" />


**⚙️ System Workflow**

    1. Webcam Input
    Captures frames in real time using OpenCV.
    
    2. Hand Landmark Detection
    MediaPipe extracts 21 hand landmarks from each frame.
    
    3. Normalization
    Landmark coordinates are normalized (position-independent).
    
    4. ML Prediction
    A trained RandomForest Classifier identifies the gesture.
    
    5. Automation Trigger
    Python executes system-level actions based on the prediction.
    
    6. Real-Time Loop
    Continuous processing with smooth, instant responses.

**🔥 What I Learned**

    Building a real-time ML system from scratch

    Gesture landmark processing & normalization

    ML model training for classification tasks

    Dealing with real-world detection challenges

    Integrating gestures with desktop automation

    Debugging and optimizing real-time pipelines

**📁 Project Files (Cleaned & Functional)**

    realtime.py → Final live system
    
    guesture_model.pkl → Trained model
    
    extract_landmaK.py → Collects normalized landmark data
    
    evaluate.py → Trains & evaluates ML model
    
    *_landmark_norm.csv → Normalized data

**🛠️ Tech Stack**

    pip install opencv-python MediaPipe Scikit-Learn
    

**📬 Contact**

If you face any problems, feel free to reach out:

Email: arafat.bd.hosen@gmail.com

**WhatsApp: +8801744805068**

**WeChat: arafat_cn**

**QQ: 3522584423**
