Face Recognition Attendance System
This project implements a face recognition-based attendance system using OpenCV and the `face_recognition` library. It captures video from the webcam, detects faces, and marks attendance for known individuals.

Features
Face Recognition: Recognizes faculty and student faces.
Attendance Tracking: Marks attendance as "present" or "absent" with timestamps.
CSV Logging: Saves the attendance data with date, name, status, and time.
Real-time Processing: Displays recognized faces and updates the attendance in real-time.

Requirements
- Python 3.x
- OpenCV
- face_recognition
- numpy

Installation
1. Clone the repository:
   git clone https://github.com/yourusername/face-recognition-attendance.git
  2. Ensure you have photos of faculty and students stored in the `photos/` folder with names matching the ones in the code (e.g., `amritha.jpg`, `navya.jpg`).

Usage
1. Run the Python script:
2. The webcam will open, and the system will try to recognize faces. If a face is recognized, the attendance will be marked as "present."
3. Press 'q' to exit the webcam feed.

Output
A CSV file named `attendance.csv` will be created, logging attendance with the current month's name as the header.

