🚗 Number Plate Detection using Python & OpenCV

A simple Python project that detects vehicle number plates from images using OpenCV and extracts text using EasyOCR. This project demonstrates the basic workflow of ANPR (Automatic Number Plate Recognition).

📌 Features

Detects number plate region from an image

Draws a bounding box around the plate

Extracts text using OCR

Simple and easy to run

🛠️ Technologies Used

Python

OpenCV

EasyOCR / PyTesseract

NumPy

📂 Project Structure
project/
│── number_plate_detection.py
│── images/
│── haarcascade_russian_plate_number.xml   (optional)
│── README.md

▶️ How It Works

Load the image

Convert to grayscale

Apply noise reduction

Detect edges using Canny

Find contours and identify plate-shaped rectangle

Crop detected plate

Apply OCR (EasyOCR) to extract text

Display detected plate and printed number

🚀 How to Run the Project
1️⃣ Install required libraries
pip install opencv-python
pip install easyocr
pip install numpy

2️⃣ Run the Python script
python number_plate_detection.py

3️⃣ Output

Detected plate will be shown in a window

Extracted text will be printed in the terminal

✅ How to Run Your Number Plate Detection Project

Follow these steps exactly:

1️⃣ Extract the ZIP file

You uploaded:

numberplatedetection_full_batch.zip

Do this:

Right-click the ZIP → Extract All

You will get a folder (example):
numberplatedetection_full_batch/

2️⃣ Open the Extracted Folder

Inside it, you should see:

Python files (.py)

A folder named images/

Maybe a Haar Cascade file

Possibly OCR model folder

3️⃣ Open Terminal / CMD inside the folder
Windows

Open folder

Click the address bar

Type: cmd → press Enter

Mac / Linux

Right-click inside folder

Select Open in Terminal

4️⃣ Install Required Libraries

Run these commands:

pip install opencv-python
pip install easyocr
pip install numpy
pip install matplotlib
pip install imutils


(Your project may need only some of these—but installing all is safe.)

5️⃣ Run the Main Python File

Look for the main script in your folder.

Usually named:

main.py

number_plate_detection.py

npd.py

or similar

Example command:

python number_plate_detection.py


If your main file name is different, replace it.

6️⃣ Check the Images Folder

Make sure:

Your vehicle images are in: images/

The script loads the correct image path

If needed, open the .py file and edit:

image = cv2.imread("images/car.jpg")


Change "car.jpg" to your file name.

7️⃣ Output

When you run the code:

A window will open showing the detected number plate

The terminal will print the extracted plate number

Some projects may save cropped plate images automatically

