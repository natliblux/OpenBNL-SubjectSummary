# OpenBNL-SubjectSummary
Jupyter notebook to query eLuxemburgensia newspaper subjects.
## Introduction
This project uses Jupyter Notebooks to encapsulate all information regarding the project.
The notebook retrieves a list of subjects for each newspaper in eLuxemburgensia. The user is then requested to select one of the subjects. A list of the newspapers linked to the chosen subject are displayed with a link to the newspaper in eLuxemburgensia allowing the user to search directly within the newspaper.
## Requirements
* Python 3.12
* [requests](https://pypi.org/project/requests/): HTTP library to run HTTP requests
* [pandas](https://pandas.pydata.org/): format the output into tabular layout
* [xml minidom](https://docs.python.org/3/library/xml.dom.minidom.html): converting XML received from the OAI call into a Document Object Model interface
## Usage
The notebook can be run online using [Binder/JupyterLab](https://mybinder.org/v2/gh/natliblux/OpenBNL-SubjectSummary/f13cab7db9d1b1da05d32d4ffdff90dbaab5daac?urlpath=lab%2Ftree%2Fsrc%2FOAI%20Subject%20Summary.ipynb).
## Result
Below is a sample of the results produced by this project.
![Sample results - Subjects per Newspaper](Sample%20Results%20-%20Subjects%20per%20Newspaper.png)
![Sample results - Newspapers for Chosen Subject](Sample%20Results%20-%20Newspapers%20for%20Chosen%20Subject.png)
