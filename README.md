# Project 1 Page Server

This is a simple flask server that reads a schedule txt file and displays each week given onto a webpage. The current week will be highlighted in bright green.

## Prerequisites

* Python 3 
* a credentials.ini file located in the syllabus folder
* a schedule.txt file (Example file given in ./syllabus/data)

## Getting Started

* Copy and/or rename credentials-skel.ini to credentials.ini and fill in the appropriate information

* Change schedule.txt to your current class schedule

### Setup
open your terminal in your project directory and run the following commands

```
make env
make install
```

If these commands do not work try this

```
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
make install
```
You must be in the virtual environment to run this project properly

## How To

### Command Line
From the project directory
```
make run
```

Navigate to you port using

```
localhost:PORTNUMBERHERE
```


## Authors

* **Justin Robles** - Jrobles@cs.uoregon.edu


