
This project is created by Job Aoushadan 
# Smart Resume Analyser 
Deatailed explanation for TATA GROUP Generative AI-Powered Resume Analyzer Task

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 
[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)   


## Source
- Extracting user's information from the Resume, I used [PyResparser](https://omkarpathak.in/pyresparser/)
- Extracting Resume PDF into Text, I used [PDFMiner](https://pypi.org/project/pdfminer/).

## Features
- User's & Admin Section
- Resume Score
- Career Recommendations
- Resume writing Tips suggestions
- Courses Recommendations
- Skills Recommendations
- Youtube video recommendations

## Usage
- Clone my repository.
- Open CMD in working directory.
- Run following command.
  ```
  pip install -r requirements.txt
  ```
- `App.py` is the main Python file of Streamlit Web-Application. 
- `Courses.py` is the Python file that contains courses and youtube video links.
- Download XAMP or any other control panel, and turn on the Apache & SQL service.
- To run app, write following command in CMD. or use any IDE.
  ```
  streamlit run App.py
  ```
- `Uploaded_Resumes` folder is contaning the user's uploaded resumes.

- Admin side credentials is `job_aoushadan` and password is `tatagroup123`. 

## Screenshots

## User side
<img src="https://raw.githubusercontent.com/Aoushadan/Smart-Resume-Analyzer/refs/heads/main/sc1.PNG">

## Admin Side
<img 
src="https://raw.githubusercontent.com/Aoushadan/Smart-Resume-Analyzer/refs/heads/main/sc2.PNG">

