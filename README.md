# Sublime Text 3 personalization

## Preferences.sublime-settings
This is the user-specific configuration settings in Sublime Text 3. 

## Python3.sublime-build
This is a generic build configuration file. This allows to run a python file using Python 3 interpreter. 

## SublimeLinter.sublime-settings
Linter basic configuration options.

## Virtualenv.sublime-settings 
This personalization allows you to run code explicitly under a Python3 virtualenv. In order to locate the correct virtualenv to use, Package Control will offer a list of virtualenvs detected automatically as per indication of a base path provided in the configuration options. 

## untitled.sublime-project [OBSOLETE; check Virtualenv above]
This file is a Sublime Text project configuration file. This allows to work with Python and __virtual environments__. 
For this project configuration to work properly you can configure things as expected or modify the configuration proposed. 

  1) Call your main program _'app.py'_.
  2) Manually create your virtualenvironment using command _'virtualenv -p python3 venv'_.
  3) Activate your virtualenvionrmenton a terminal using command _'source venv/bin/activate'_.
  4) Then, you can start programming and building python code in your virtualenv.
