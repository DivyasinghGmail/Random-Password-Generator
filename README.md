# Random-Password-Generator


![207718](https://user-images.githubusercontent.com/86322884/131230322-8c890619-3580-4904-8a7d-658008762f41.png)


Random Password Generator is written in Python using Tkinter for GUI. The project file contains python scripts (random password generator.py and pwgenfunc.py). This is a simple GUI based project which is very easy to understand and use. Talking about the system, the user can generate a random password according to different sizes.

In order to generate a password first, the user has to select a size range using the button. It also displays with a visual color-coded system which indicates the strength of the password, starting from Low to Strong password strength. After generating a random password, the system displays it in the clipboard where the user can copy and paste easily.

This GUI based Password Generator provides the simplest way for generating a strong password for the users. In short, this project only focuses on generating random passwords.

In order to run the project, you must have installed Python, on your PC. This is a simple GUI Based system, specially written for the beginners.

With growing technology, everything has relied on data and securing these data is the main concern. Passwords are meant to keep the data safe that we upload on the Internet. 
An easy password can be hacked easily and all the personal information can be misused. In order to prevent such things and keep the data safe, it is quite necessary to keep our passwords very strong.
Let’s create a simple application which can randomly generate strong passwords using Python Tkinter module.
This application can generate random password, with the combination of letters, numerics, and special characters. One can mention length of the password based on requirement and can also select the strength of the password.

Features:

1.Displays Password Strength

2.Select password size

In this  Random password generator GUI application, we are going to use two 3 modules. Firstly, the Tkinter module for creating an application window. Secondly, pyperclip module for copying the generated password. Now, remember these two modules are not inbuilt modules. So you have to install them using the pip install command. The third and final module we are going to use is a random module to generate the random password finally. The quick logic for this GUI application is going to be like this: Firstly, We will create import the necessary modules. Then we will create the application window. After that, we will generate a random password and copy it. Afterward, In the end, we will create some buttons to make our password generator application more interactive for the user. Because after all, it’s a GUI.

Modules needed: 

import random

import pyperclip

from tkinter import * from tkinter.ttk import *

Understanding the Code of GUI Application

Firstly, Let’s understand the coding now with some technical terms. Here, we are going to explain the code stepwise. So that if you have some knowledge of python you will be able to make this password generator application on your own by just reading this section.

Step1: Firstly, Import necessary modules ( Tkinter, pyperclip and random)

Step2: Then, Initialize Tkinter using Tk() method

Step3: After that, Create an application window for GUI application using the geometry method of Tkinter

Step4: Declare 2 variable. One for storing the generated password and another one for taking password length input from user.

Step5: Then, Define the generate password method.

Step6: Define the copy to clipboard method.

Step7: Then, Create Button widgets and set commands as per the above defined methods.

Step8: Finally, Run infinite mainloop to run the application.



![image](https://user-images.githubusercontent.com/86322884/131265303-27fe24e6-9c38-4d04-acc9-6c0f1dcc0748.png)




