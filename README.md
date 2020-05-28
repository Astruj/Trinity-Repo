# Personalized-summary-from-eye-gaze

## Run:
cd Laboratory/Integration/
python3 new_main.py

## Dependencies

### python3-pip

* PyQt5
* MSS
* pynput
* OpenCv
* Numpy
* pytesseract
* Wnck
* Gtk
* Tensorflow

### apt-get

* tesseract-ocr

### Installing OCR tool

```bash
sudo apt-get install tesseract-ocr
```
## Config Files

* main_cofig
    1. [0] Determines when to start or stop capture_gaze script.
    1. [1] Determines when to store the captured gaze values into a variable.
    1. [2] Determines whether the program has been successfully calibrated or not.

* config
    1. [0] Determines when to start or stop the elg_demo script to calibrate the program.
    1. [1] Determines when to open the calibration window and run the subsequent script.
    1. [2] Determines when to run the Wait GUI and script.
    1. [3] Determines when to save the captured gaze values into a file.
    1. [4] Determines when to capture the gaze values and store it into a variable.

> The number within third bracket determines the index value of that line in the file.
