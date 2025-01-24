# Car Parking Management System

This project is a **Car Parking Management System** designed to automate parking slot allocation, manage vehicles, and calculate parking fees. The system is built using Python, Flask, HTML, and CSS for a web-based interface.  

---

## Features

- **Slot Management**: Allocate and free parking slots dynamically.  
- **Vehicle Registration**: Record vehicle details such as license plates.  
- **Billing System**: Calculate parking fees based on the time spent.  
- **User-Friendly Interface**: Simple and intuitive web interface for users.  
- **Region of Interest (ROI)**: Select ROI for car detection using `selectingROI.py`.  
- **Video Input Support**: Demonstrate functionality with a sample video.  

---

## Technologies Used

- **Backend**: Python (Flask)  
- **Frontend**: HTML, CSS  
- **Libraries**: OpenCV (for ROI selection and video processing), NumPy, etc.  

---

## Prerequisites

- Python 3.x  
- Flask (`pip install flask`)  
- OpenCV (`pip install opencv-python`)  

---

## Installation

1. Clone this repository:  
   ```bash
   git clone https://github.com/vignesh3254/car-parking.git
   cd car-parking
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the application:
   ```bash
   python flask.py
   
## Project Structure
- **flask.py:** Main application file for running the Flask server.
- **main.py:** Core logic for parking management.
- **selectingROI.py:** Script for selecting the Region of Interest in video frames.
- **static/:** Contains static assets like CSS, JS, and images.
- **carParkingInput.mp4:** Sample video for demonstration.
