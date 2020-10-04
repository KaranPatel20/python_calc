# A Calculator made in python

## This is python_calc assignment assigned on 28/09/2020 

This assignemt was completed using various basic GUI features of Python. This model is perfect for understanding how the basic GUI features work in Python.

### Steps to create the calculator

### Step-1:
Create test.py, import sys package. Now import QApplication, QLabel and Qwidget into test.py from PyQt5.QtWidgets.
	
1. Now, make an application using QApplication()
2. Using QWidget() give the dimensions of the window as per required.
3. Print a hello message (This is just for checking) and then end the window using show().

### Step-2:
Create view.py, import Qt, QMainWindow, QLineEdit, QGridLayout, QPushButton, QVBoxLayout and Qwidget into view.py from PyQt5.QtWidgets.
	
1. Now, construct class GUI which calls constructor of QMainWindow.
2. Using different widget and layout functions, define the calculator's look and layout as needed.
3. Create a display bar at top for showing the entered digits in a calculator.
4. Now using tuples, define position of each and every button in the calculator layout.
5. Construct the grid layout of buttons perfectly.

### Step-3:
Create main.py and import sys package.
	
1. Define the main function.
2. Create and call an instance of QApplication.
3. Show the GUI using GUI() and show() methods.

### Step-4:
Create model.py and add the following in the module.

1. Define evaluateExpression method in it.
2. Pass the expression in the above listed method and check whether it throws any exception or not, if not then print the result.

### Step-5:
Create controller.py. In this module add the following things:

1. Define a class named Controller.
2. Build a constructor which calls model and view parameters in it.
3. Define 3 functions in it:
	1. calculateResult: for evaluating result of expression.
	2. buildExpression: for validating and building the expression.
	3. connectSignals: to connect the expression through the buttons we defined in Step-3.


#### After following the above mentioned steps, open an Anaconda cmd and enter the location where you have stored the package of python_calc or if you're using only python then install PyQt5 using the command 'pip install pyqt5'.
#### Now, try to run to the main.py file, it will show you a layout like a basic calculator and then by entering values you can do your calculations on your newly created basic calculator.
#### On a perfect execution of this calculator, you should the following output in your screen
![Output Screen](/Output/Output_1.png)