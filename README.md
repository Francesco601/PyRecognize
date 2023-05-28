# PyRecognize

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 

![Screenshot](https://github.com/Francesco601/PyRecognize/blob/main/Screenshot_20230528_055729-1.png)


**Python machine learning program that can be trained to recognize any  faces in photos** 

## Instructions:
---
1) Create a python virtual environment in Linux or Mac with the following command:
  - python3 -m venv venv
  
2) Activate the environment after making sure you are in the directory you just created:
  - source  venv/bin/activate
3) clone this repository with the requirements.txt file and install requirements:
  - python -m pip install -r requirements,txt
5) Use on Linux and Mac: "python recognize.py -h (or --help)" provides usage instructions.
6) "python recognize.py --train <path to images>"  which should be  a directory of images to train the program for specific faces.
7) "python recognize.py --validate"  to run tests 
8) "python recognize.py --test <path to image>" to test on an unknown image.
  
  
