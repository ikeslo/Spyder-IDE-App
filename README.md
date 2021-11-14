# Spyder-IDE-App-v5.1.5
Fix Spyder v5.1.5

# Spyder 5.1.5 | Needs Python 3.9.5

## Using anaconda via the terminal ##

## Make sure to open the propper environment or create a new one before you continue ##
## Do not use the base environment. That's one reason you keep having Spyder crashes ##

# This removed the old python version in your environment 
conda uninstall python=version

# Here's an example: 
conda uninstall python=3.9.7

# Install the version of python you need. Like the one the spyder app wants you to use. Using:
conda install python=3.9.5

# Install the kernel version the app wants you to install:
conda install spyder-kernels=2.1

# Install Spyder full functionality using:
conda install numpy scipy pandas matplotlib sympy cython

# Close everything and reopen Spyder and change your default environment to the one you just created
# Everything should work fine now.
