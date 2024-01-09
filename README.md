# FARZI _ Counterfeit Banknote Detection

Detects Counterfeit Indian Currency using Image Processing Techniques

## 	Overview
The aim of this project is to test the authenticity of Indian currency notes by preparing a system which takes the image of currency bill as input and gives the ﬁnal result by applying various image processing and computer vision techniques and algorithms. 
This currency authentication system has been designed completely using Python language in Jupyter Notebooks. **OpenCV** library has been used for image processing and **Tkinter** library has been used for building the GUI. 

## Libraries and Tools
1. OpenCV
2. Tkinter
3. Numpy
4. Matplotlib
5. Jupyter Notebook

## Dataset
This currency detection currently works only for Indian Currency notes of denomination 500. The dataset used for this purpose is included in this repository and has been custom- built by collecting necessary images from various sources. To know more about dataset refer to the report of this project present in this repository. 

## Structure
1. **Dataset:** Contains all necessary images. This directory also contains images of real 500 rupee notes which you can use to test the system. Read the report to know more about structure of dataset.
2. **Fake Notes:** Contains images of fake 500 rupee notes. You can use these images to test the system if you want.
3. **500_testing.ipynb:** This notebook processes input image of 500 denomination currency bills.
5. **controller.ipynb:** This notebook is the main notebook which takes the input, runs all necessary notebooks and displays the output.
6. **gui_1.ipynb:** This notebook produces a GUI to take the input data from the user.
7. **gui_2.ipynb:** This notebook produces a GUI to display the result.
8. **FAKE_CURRENCY_DETECTOR_REPORT:** Report of this project. This file contains the complete information of the project. Refer to this report file for methodology, snapshots, results and other details regarding this project.


