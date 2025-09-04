# YOLOv8 Computer Vision Projects

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![Framework](https://img.shields.io/badge/Framework-Ultralytics%20YOLOv8-orange)
![License](https://img.shields.io/badge/License-MIT-green.svg)

A curated collection of practical computer vision projects built with Ultralytics YOLOv8. This repository includes examples ranging from basic object detection on images to real-time object counting in video streams using the SORT tracking algorithm.

---

## 🌟 Features

-   **Basic Inference:** Simple scripts to run YOLOv8 detection on images and webcam feeds.
-   **Car Counter:** A complete application to detect, track, and count cars passing through a designated line in a video.
-   **People Counter:** A similar application tailored for detecting, tracking, and counting people.
-   **Object Tracking:** Integration of the Simple Online and Realtime Tracking (SORT) algorithm for robust object tracking.
-   **Organized Structure:** Code is organized into chapters and specific projects for easy navigation.

---

## 📂 Project Structure

.
├── yolo-weights/
│   ├── yolov8l.pt
│   └── yolov8n.pt
├── chapter 5 - running yolo/
│   ├── yolo-basics.py
├── chapter 6 - yolo with webcam/
│   ├── yolo_webcam.py
├── project 1 - car counter/
│   ├── car_counter.py
│   ├── graphics.png
│   ├── mask.png
│   ├── sort.py
├── project 2 - people counter/
│   ├── people_counter.py
│   ├── graphics.png
│   ├── mask.png
│   ├── sort.py
├── videos/
│   ├── (Your video files for counters)
├── requirements.txt
└── README.md


---

## 🚀 Getting Started

Follow these instructions to get a local copy up and running.

### Prerequisites

-   Python 3.9 or later
-   `pip` package manager

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/YOUR_USERNAME/YOLOv8-Object-Counting-Projects.git](https://github.com/YOUR_USERNAME/YOLOv8-Object-Counting-Projects.git)
    cd YOLOv8-Object-Counting-Projects
    ```

2.  **Create a Virtual Environment (Recommended):**
    ```sh
    # For Windows
    python -m venv venv
    .\venv\Scripts\activate

    # For macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

---

## 🏃‍♂️ How to Run the Scripts

Make sure you have activated your virtual environment before running any script.

### 1. Basic Image Detection
This script runs YOLOv8 detection on a static image and displays the result.
```sh
python "chapter 5 - running yolo/yolo-basics.py"
2. Real-time Webcam Detection
This script uses your webcam for real-time object detection.

Bash

python "chapter 6 - yolo with webcam/yolo_webcam.py"
3. Car Counter
This script processes a video file to count cars. You will need to place your video file in the videos directory and update the path in the car_counter.py script.

Bash

python "project 1 - car counter/car_counter.py"
4. People Counter
This script processes a video file to count people. Similarly, update the video path in people_counter.py.

Bash

python "project 2 - people counter/people_counter.py"
🙏 Acknowledgments
Ultralytics YOLOv8: For their powerful and easy-to-use object detection model. Visit their GitHub.

SORT Algorithm: For the simple and effective object tracking implementation. Visit the original repository.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.