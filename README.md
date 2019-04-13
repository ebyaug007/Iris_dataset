This project to study various basic concepts of machine learning

Tasks involved are
1. Loading dataset
2. Summarizing dataset
3. Visualizing dataset
4. Evaluating various algorithms
5. Making predictions

Reference https://machinelearningmastery.com/machine-learning-in-python-step-by-step/

Packages required are
1.scipy
2.numpy
3.matplotlib
4.pandas
5.sklearn

To check whether the packages are installed type the below command in terminal

	pip3 list| grep -e scipy -e numpy -e matplotlib -e pandas -e sklearn

If all the packages are listed you are good to go.
Any of the packages are missing use the below command to install the same

	pip3 install <package_name>


While loading the packages for your project if the below error comes associated with matplotlib
	import tkinter as Tk
	ModuleNotFoundError: No module named 'tkinter'

Use the below command to install tkinter
	sudo apt-get install python3-tk

Tkinter is the defacto GUI of python(For more details refer https://wiki.python.org/moin/TkInter)

After loading the packages, we need to load the dataset. In the python program I've loaded the dataset directly from UCI machine learning repo. You can download the same and point to that location if needed.

A pandas function called read_csv() is used to load the dataset.
