# Run Guide

Firstly install Python 3.9.

Make sure venv (Virtual Environments) and pip (Python Package Manager) are installed.


Run these commands in root directory of project:
```
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter notebook
```

For geemap --- make an account with the google earth API. You need to register and sign up - it's easy with an academic email address.

Basically, geemap is a Python interface to automate the whole process of water cell calculation. (I think I would run it overnight to collect all the data.)

The other half of the project (interpolation), involves using Chambolle-Pock/proximal/convex methods to 'fill in the gaps'.


As an extension (my personal recommendation), perhaps look into using more modern techniques (like Gaussian Processes) to both fit the data and obtain uncertainty intervals :).