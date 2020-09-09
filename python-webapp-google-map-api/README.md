## Python Webapp using Google Maps API

Build and deploy a simple Python app that serves a simple webpage that fetches data from the Google Maps API.

### 0. Setup

0. **Installing Python**  <br>
We will be using `Python 3.6.5` for this workshop. If you have another version of Python, it should still work but you may run into dependency issues. Here's the link to the [download for Python 3.](https://www.python.org/downloads/release/python-365/) Check if you've installed it properly by making sure you can run `python` and `pip` in the terminal.

1. **Installing Git** <br>
Git is a version control tool. You'll use this to download the repository and switch between branches! You can download the command line version here https://git-scm.com/downloads or if you prefer the GUI, https://www.gitkraken.com/

2. **Project setup** <br>
Clone this project somewhere convenient. You can do this by opening your command prompt and navigating to a convenient folder. <br><br>
e.g. `cd ~/Documents` <br><br>

3. **Installing dependencies** <br><br>
There are a few Python libraries we will be using today that will help us build today's app. <br> <br>
`pip install flask requests`

4. **API Keys** <br><br>
We'll be integrating our app with the Google Maps API. Go ahead and get that key here: https://developers.google.com/places/web-service/get-api-key. Follow the 5 steps to get your API key. Create a file called `secrets.txt` with your API key and put that in this folder.

### 1. The Backend
**What is a backend?**

"Backend" code is the stuff that powers everything on the internet from behind the scenes.

**What is Flask?**

Flask is a *web framework* written in python. Basically, it gives you the basic tools to build a web application, meaning you can serve websites and other cool stuff.
