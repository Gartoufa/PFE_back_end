Wellcome to my back-end project

===================================

## Quick start
Follow this quick start to install and run the project

### Creating an environment 
After cloning the repo create an enviroment with
`python -m venv .venv`

### Activating the environment with
If you are on windows (run powershell as an Administrator):
`.\<venv>\Scripts\Activate.ps1`

If you are on linux :
`source <venv>/bin/activate`

### Install the dependencies

`pip install -r requirements.txt`

### Lauch the script 
Using uvcorn:
`uvicorn main:app --reload`
