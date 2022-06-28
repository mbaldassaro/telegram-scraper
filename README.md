# Collecting & Analyzing Telegram Data

This repository contains a Telegram Scraper Jupyter Notebook with Python code for to collect and analyze data from public channels on the Telegram messaging platform.  

Here are the steps to run this Jupyter Notebook with all required dependencies on your computer. Note: The steps below assume that you have Git and the Github Command Line Interface (CLI) installed on your system. If not, first download [Git](https://git-scm.com/downloads) and then [Github CLI](https://cli.github.com/) prior to executing the following commands.

1. Via the command line, clone this repository and change into the main directory folder

> gh repo clone https://github.com/mbaldassaro/telegram-scraper.git && cd telegram-scraper

2. Create a virtual environment and activate it

> py -3 -m venv env && env\Scripts\activate.bat

(if you are using a Mac: python3 -m venv env && source env/bin/activate)

3. Install the packages and dependencies using the requirements.txt file

(env) > pip3 install -r requirements.txt

4. Launch the Jupyter Notebook in your preferred IDE

e.g., if you are using the Microsoft Visual Studio Code IDE:

* On the command line, type CODE and hit enter. This opens the VS Code IDE and sets your virtual environment (and all included dependencies) as the environment for the IDE. 
* Open the Jupyter Notebook from folder you cloned to your local computer 
