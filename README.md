# Face Recognition AI with Python Project

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)

## Introduction
The Face Recognition AI with Python Project is a web application that leverages machine learning to detect and recognize faces in images or video streams. It provides a powerful and easy-to-use interface for face recognition tasks.

## Features
- Real-time face detection and recognition
- Support for image and video input
- User-friendly interface for uploading and processing images
- Database for storing known faces
- High accuracy using state-of-the-art machine learning models

## Technologies Used
- Programming Language: Python
- Libraries: OpenCV, dlib, face_recognition
- Backend: Flask
- Frontend: HTML, CSS, JavaScript
- Database: SQLite

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/sanjaikrp/Face-Recodnition.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Face-Recodnition
    ```
3. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
4. Install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```
5. Set up the environment variables:
    ```sh
    cp .env.example .env
    ```
6. Start the development server:
    ```sh
    flask run
    ```

## Usage
1. Open your web browser and navigate to `http://localhost:5000`.
2. Use the provided interface to upload images or start a video stream.
3. The application will detect and recognize faces, displaying the results on the interface.
