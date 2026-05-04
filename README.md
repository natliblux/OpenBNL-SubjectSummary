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
The notebook can be run online using [Binder/JupyterLab]().
## Result
Below is a sample of the results produced by this project.
![Sample results]()
