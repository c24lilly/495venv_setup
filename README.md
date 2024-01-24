# Setting up ECE 495 Virtual Environment

*I know we already did a bunch of set up, but in building our ICEs and Labs, I realized we had some compatibility issues with a few packages in our prior setup. Therefore, we are going to create a virtual environment that you can use for the rest of class!*

(1) Fork this repository.

(2)  You will need to create a new environment that uses **python 3.10.11** with the following packages: nengo 3.2, tensorflow 2.10.1, nengo-dl 3.6.0, nengo-gui, black[jupyter], matplotlib, scikit-learn, and other dependencies. The process to do so is to create a new environment using Python 3.10.11, activate the new environment, then download the packages using requirements.txt in this repository. 

(3)[Download Python 3.10.11](https://www.python.org/ftp/python/3.10.11/python-3.10.11-amd64.exe) - This link will download the *.exe file for Python 3.10.11. Double click the downloaded file to start the installer. Be sure to check the box that says add to PATH!

(4) Create your new environment using Python 3.10.11.  

If you are using conda, these commands should do the trick:  
`conda create --name 495venv python=3.10` -- This command gives your new environment a name of *495venv*, however you can name it whatever you'd like.  
`conda activate 495venv` -- This command activates the environment so that you can install other programs within that environment. You might see the name inside of your brackets change from *base* to the name of your new environment.

If you are using Windows without conda, these commands should work inside of your Command Prompt (**note: must use python 3.10**):  
Use your path to your downloaded Python 3.10.11 in the following command (the path below is only an example of what it might look like):  
`C:\Users\C2XName\AppData\Local\Programs\Python\Python310\python.exe -m venv 495venv` -- This command gives your new environment a name of *495venv*  
`495venv\Scripts\activate` -- This command activates the environment so that you can install other programs within that environment. You might see the name inside of your brackets change from *base* to the name of your new environment. 
  
Note: I don't think anyone is using Linux or Mac, but please let me know if you are and need additional assistance.
  
(5) Once you have activated your environment, cd to the directory in which your requirements.txt is stored, then run the following command:  
`pip install -r requirements.txt`  
  
(6) From your activated terminal, launch your code editor. If you're using VS code, this command should do it: `code .` Within VS Code, in the search bar at the top type `>Terminal: Create New Terminal`. Select your _495venv_ environment if/when prompted. 
  
(7) Open nengoDNN_setuptest.ipynb. Try to run. It may ask you to install a Jupyter extension - if it does, do it! If this code runs without error, everything should be ready to go for ICE1!

**Thanks team!**

