# Face Recognition Based Attendance System

A Python-based attendance management system that uses **face recognition** to automatically mark attendance. The project includes a simple **Tkinter GUI** so that the system can be operated easily through an interactive interface.

## Overview

This project provides a simple way to manage student registration and daily attendance using face recognition. It uses OpenCV for face detection and recognition and stores student and attendance information in CSV files.

The GUI is developed using Python's **Tkinter** library.

## Technologies Used

* **Python**
* **Tkinter** – GUI development
* **OpenCV** – Image processing and face recognition
* **LBPH Face Recognizer** – Face recognition
* **NumPy** – Numerical operations
* **Pandas** – Data handling
* **CSV** – Student and attendance data storage
* **Datetime** – Date and time management

## Features

* Interactive and easy-to-use GUI
* Face recognition based attendance
* Password protection for new person registration
* Student details stored and updated through CSV files
* Automatically creates a daily attendance CSV file
* Records attendance with date and time
* Displays live attendance updates on the main screen
* Attendance table includes:

  * ID
  * Name
  * Date
  * Time
* Password change option
* Help option available through the menu bar

## How It Works

1. Register a new person through the GUI.
2. The system collects face images for the registered person.
3. OpenCV is used to process the captured images.
4. The LBPH Face Recognizer is used for face recognition.
5. When a registered face is recognized, attendance is recorded.
6. Attendance is saved with the person's ID, name, date, and time.
7. The current day's attendance is displayed in the GUI.

## Project Structure

```text
Face-Recognition-Based-Attendance-System/
│
├── main.py
├── haarcascade_frontalface_default.xml
├── README.md
└── LICENSE
```

## Screenshots

### Main Screen

![Main Screen](https://user-images.githubusercontent.com/37211676/58502148-97ec2a00-81a3-11e9-963e-674b9c3e05dc.png)

### Attendance Display

![Attendance Display](https://user-images.githubusercontent.com/372116)
