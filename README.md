# Invisible Cloak - Django + OpenCV Project

A fun real-time **Invisible Cloak effect**, built using **Python, OpenCV, and Django**.  
This web app replaces a red cloak in front of your webcam with the background, making it appear invisible.

---

## Features

- Real-time video streaming from your webcam.
- Red cloak detection using **HSV color segmentation**.
- Mask refinement using **morphological operations**.
- Cloak area replaced with captured background.
- Django web interface to stream the video in the browser.

---

## Requirements

- Python 3.8+  
- Django 4.x  
- OpenCV (`opencv-python`)  
- Numpy  

You can install all dependencies with:

```bash
pip install -r requirements.txt
