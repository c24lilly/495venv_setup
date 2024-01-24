# Testing environments

**This is for test purposes only. Cadets - please do not do this yet!**

(1) Fork this repository.

(2) [Download Python 3.10.11](https://www.python.org/ftp/python/3.10.11/python-3.10.11-amd64.exe) - be sure to check the box that says add to PATH!

(2) You will need to create a new environment that uses **python 3.10.11** with the following packages: nengo 3.2, tensorflow 2.10.1, nengo-dl 3.6.0, nengo-gui, black[jupyter], matplotlib, scikit-learn, and other dependencies. The process to do so is to create a new environment, activate the environment, then download the packages using requirements.txt in this repository. 

If you are using conda, these commands should do the trick:  
`conda create --name 495venv python=3.10` -- This command gives your new environment a name of *495venv*, however you can name it whatever you'd like.  
`conda activate 495venv` -- This command activates the environment so that you can install other programs within that environment. You might see the name inside of your brackets change from *base* to the name of your new environment.

If you are not using conda, these commands should work inside of your Command Prompt (**note: must use python 3.10**):  
Windows:  
Find your path to your downloaded Python 3.10.11  
`C:\insert your path that your Python 3.10.11 exe file is held in\python.exe -m venv 495venv` -- This command gives your new environment a name of *495venv*  
`495venv\Scripts\activate` -- This command activates the environment so that you can install other programs within that environment. You might see the name inside of your brackets change from *base* to the name of your new environment. 
  
Linux/Mac:  
I don't think anyone is using Linux or Mac, but please let me know if you are and need additional assistance.
  
Once you have activated your environment, cd to the directory in which your requirements.txt is stored, then run the following command:  
`pip install -r requirements.txt`  
  
(3) From your activated terminal, launch your code editor. If you're using VS code, this command should do it: `code .` Within VS Code, in the search bar at the top type `>Terminal: Create New Terminal`. Select your _495venv_ environment if/when prompted. 
  
(4) Open nengoDNN_ICE2.ipynb. Try to run. If it runs, everything should be ready to go. 

