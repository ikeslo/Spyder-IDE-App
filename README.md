# Spyder-IDE-App-v5.1.5
- Fix your Spyder problems

## Spyder 5.1.5 | Needs Python 3.9.5

## We'll fix them using anaconda via the terminal ##

## Make sure to open the propper environment or create a new one before you continue 
-  Do not use the base environment. That's one reason Spyder keeps crashing. 

## This removed the old python version in your environment 
conda uninstall python=version

-  Here's an example: 
conda uninstall python=3.9.7

## Install the version of python you need. Like the one the spyder app wants you to use. 
conda install python=3.9.5

## Install the kernel version the app wants you to install:
conda install spyder-kernels=2.1

## Install Spyder full functionality:
conda install numpy scipy pandas matplotlib sympy cython

## Close everything and reopen Spyder. 
- Now change your default environment to the one you just created in your Spyder Python interpreter
## Everything should work fine now.
