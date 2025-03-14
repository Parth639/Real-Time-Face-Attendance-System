⏳📸 Real-Time Face Attendance System

🔍 Overview
The **⏳📸 Real-Time Face Attendance System** is an 🤖 automated attendance tracking solution that leverages 🧠 face recognition technology to accurately 📝 record attendance in real time. It utilizes a 🏋️ CNN-based face recognition model from the `face_recognition` 📚 (built on `dlib`) to extract 📏 128-dimensional facial embeddings for 🎯 accurate user identification. The system is integrated with ☁️ Firebase for real-time 📡 database updates, making it suitable for 🏫 schools, 🎓 universities, and 🏢 corporate offices.

 ⭐ Features
- ⏳📸 Real-time Face Recognition**: Detects and recognizes 😃👀 using a 🏋️ pre-trained CNN model.
- ✅ Automated Attendance Marking**: Prevents 🚫 duplicate 📝 entries by tracking attendance ⏰ timestamps.
- 🗄️ Database Integration**: Uses ☁️ Firebase for 📡 real-time data storage and retrieval.
- 🖥️ User-Friendly Interface**: Displays 🧑📄 user info and attendance 📊 status.
- 📈 Scalability**: Capable of handling 📊 multiple users efficiently.

 🛠️ Technologies Used
- 🐍 Python**: Core programming language for the system.
- 📸 OpenCV**: For 👀 face detection and 🖼️ image processing.
- 📚 Face Recognition Library (dlib-based CNN)**: For extracting 🔑 unique facial embeddings.
- ☁️ Firebase**: Cloud 🗄️ database for ⏳ real-time attendance storage.
- 🐙 GitHub**: 📂 Version control and project collaboration.

⚙️ Installation
🔧 Prerequisites
Ensure you have 🐍 Python installed on your 🖥️ system. Then, install the required 📦 dependencies:
```bash
pip install opencv-python
pip install face_recognition
pip install firebase-admin
pip install numpy
```
🔥 Setting Up Firebase
1. Create a ☁️ Firebase project and enable 🔄 Firestore Database.
2. Download the `serviceAccountKey.json` 📂 from Firebase and place it in the project 📁 directory.
3. Modify the ☁️ Firebase configuration in the script.

🚀 Usage
1. Run the script to start the 📸 face recognition system:
   ```bash
   python Main.py
   ```
2. The system will 🔍 detect and recognize 😃, updating attendance records in ☁️ Firebase.
3. View the 📊 attendance logs in the ☁️ Firebase database.

👤 Authors
1.Parth Shah  
🐙 GitHub: https://github.com/Parth639   
💼 LinkedIn:https://www.linkedin.com/in/parth-shah-68695b281/

2.Yashika Sonchatra 
🐙 GitHub:    
💼 LinkedIn:
