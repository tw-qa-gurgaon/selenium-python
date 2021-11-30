# selenium_python
This repository is dedicated for writing the automation test cases in python using selenium

## Test Covered
* UI

## Technology used
* Python 3.8 (and above)
* Selenium 4.0
* Pytest 6.2.5
* Allure-pytest 2.9.45
* WebDriver-Manager

## Pre requisites: <br>
* Python 3 <br>
* IDE (Any)

-------------------------------------------------------------------------
## Steps to run:
1.Clone GIT repository in named directory. <br>
**_Run:_**
```
     > cd ~/workspace/
     > mkdir thoughtworks
     > git clone https://github.com/tw-arihant/selenium_python.git
```   
2.Create virtual environment of python
```
python3 -m venv venv
```
3.Activate the venv
```
source ./venv/bin/activate
```
          ** If you face permission error with the above command try
          ```
          chmod -R 777 ../selenium-python
          ./venv/bin/activate
          ```
4Install the dependencies that are mentioned in the script
```
pip install -r requirements.txt
```
     ** In case the above command does not work try
     ```
     pip3 install -r requirements.txt
     ```
* If pip does not work go to the requirements.txt file and select option install dependencies in IDE

5.To run the tests using cmd use: 
```
pytest -v -s location/test_name --browser=browsername
```
* Default browser = Chrome

* Example: 

```
pytest -s -v testCases/test_login.py --browser=chrome
pytest -s -v testCases/test_login.py
```     
## Author
* Arihant Jain
* Ayushi Arora
