# Mass Attendance System

A web-based mass attendance system using facial recognition technology powered by Flask, OpenCV, dlib, and machine learning.

## Features

- 🎯 **Real-time Face Recognition**: Uses Haar Cascade, dlib, and K-Nearest Neighbors (KNN) algorithm  
- 📝 **Student Registration**: Capture facial data through webcam  
- ✅ **Attendance Tracking**: Automatically records attendance with timestamps  
- 📊 **Attendance Reports**: View attendance records in CSV format  
- 👥 **Student Management**: Add/remove students from the system  
- 🌓 **Dark/Light Mode**: User-friendly interface with dark mode support  
- 📱 **Responsive Design**: Works on both desktop and mobile devices  
- 🔊 **Text-to-Speech**: Audio feedback for important actions  

## Technologies Used

- **Backend:** Python, Flask  
- **Computer Vision:** OpenCV, Haar Cascade, dlib  
- **Machine Learning:** scikit-learn, KNN classifier  
- **Frontend:** HTML5, CSS3, JavaScript  
- **Data Storage:** Pickle files for facial data, CSV for attendance records  

## Installation

### Prerequisites

- Python 3.7+  
- Webcam  
- pip package manager  

### Steps

1. Clone the repository:  
   ```bash
   git clone https://github.com/AlokTheDataGuy/mass-attendance.git  
   cd mass-attendance
   ```

2. Install the required packages:  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:  
   ```bash
   python add_faces.py
   python app.py
   ```

4. Open your web browser and go to `http://localhost:5000` to access the system.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.