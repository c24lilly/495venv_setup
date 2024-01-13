# Testing environments
because computers hate me

(1) Fork this repository.

(2) You will need to create a new environment with the following packages: python 3.10, nengo 3.2, tensorflow 2.10.1, nengo-dl 3.6.0, nengo-gui, black[jupyter], matplotlib, scikit-learn, and other dependencies. The process to do so is to create a new environment, activate the environment, then download the packages using requirements.txt. 

If you are using conda, these commands should do the trick:
`conda create --name py3.10-nengo3.2 python=3.10` -- This command gives your new environment a name of *py3.10-nengo3.2*
`conda activate py3.10-nengo3.2` -- This command activates the environment so that you can install other programs within that environment. You'll see the name inside of your brackets change from *base* to the name of your new environment.

If you are not using conda, these commands should work:
Windows:
**i need help here**

Linux/Mac:
**i need help here**

Once you have activated your environment, cd to the directory in which your requirements.txt is stored, then run the following command:
`pip install -r requirements.txt`

(3) From your activated terminal, launch your code editor (mine is VS code): `code .`

(4) Open nengoDNN_ICE2.ipynb. Try to run. If it runs, everything should be ready to go. 

