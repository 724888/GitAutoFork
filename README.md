Chinese [here](README_CN.md)
# GitAutoFork
Auto fork for gitstar.cn
## Installation
Install Python 2.x,run```python --version```and```pip```for a test.  

To install pip, securely download [get-pip.py](https://bootstrap.pypa.io/get-pip.py)

Then run the following:

> python get-pip.py

If you have downloaded it,skip the step.  
MAKE SURE that you have installed ```requests```.
> pip install -r requirements.txt

## Usage
### Step 1
Clone the repo  
```git clone https://github.com/acelwiker/GitAutoFork.git && cd GitAutoFork```

### Step 2
Open```settings.py```, replace variables with your own infomation.
```
#############settings#############
NAME		= "1" #GitStar username
PASSWORD	= "1" #GitStar password
GITNAME		= "1" #GitHub username
GITPASSWORD	= "1" #Github password
#############settings#############
```
### Step 3
Run```python -u main.py```  
Everything is ok,hooray!
