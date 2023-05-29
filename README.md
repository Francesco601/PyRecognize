# PyRecognize

**Python machine learning program that can be trained to recognize any  faces in photos** 

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 

## Examples of recognizer in action

![Screenshot](https://github.com/Francesco601/PyRecognize/blob/main/Screenshot_20230528_070939.png)

![Screenshot](https://github.com/Francesco601/PyRecognize/blob/main/Screenshot_20230528_055729-1.png)




## Instructions:
---
1) Create a python virtual environment in Linux or Mac with the following command:
  ```bash
  python3 -m venv venv
 ``` 
2) Activate the environment after making sure you are in the directory you just created:
```bash
    source  venv/bin/activate
 ```   
3) clone this repository with the requirements.txt file and install requirements:
```bash
   python -m pip install -r requirements.txt
 ```  
5) Use on Linux and Mac: 
```bash 
    python recognizer.py -h (or --help) 
   ``` 
   provides usage instructions.
   
 ```bash 
 python recognizer.py --train <path to images>
 ``` 
 which should be  a directory of images to train the program for specific faces.
 ```bash
    python recognizer.py --validate 
 ```
 to run tests 
  ```bash 
   python recognizer.py --test <path to image> 
   ```
   to test on an unknown image.
  
  
