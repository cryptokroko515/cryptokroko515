# Readme for beginners, how to set up a "Python Virtual environment". I am a beginner, so if you see anything wrong, let me know. 
# Great tip : https://explainshell.com/ 
# All is provided without any guarantee. I am not a financial advisor. Use at your own risk.

# Assumptions : Raspberry Pi3B+, Raspbian (could and should work on other models)

## Installation & Requirements

Installation & Requirements
Log in to terminal with SSH or attach the Raspberry Pi to a HDMI monitor. 

Next we are going to make a virtual environment with Python3 
- sudo apt-get install python3-venv -y

Then you are going to make a new folder. For example : my_venv
- python3 -m venv ~/my_venv

Activate the new folder:
source ~/my_venv/bin/activate

## CONGRATULATIONS : you have now made a virtual environment on your raspberry pi

Go to the folder with:
(my_venv) pi@raspberrypi:~ $ cd my_venv
(my_venv) pi@raspberrypi:~/my_venv $ 
