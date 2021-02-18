Programs covers the migration of python2 code to python3.
-------------------------------------------------------------------

python2to3.py file contains a Python program that utilizes the library lib2to3 to transform Python 2 application source code
into  a Python 3 application.

the command to convert is as follows:
2to3 -w python2to3.py

The optional -w flag indicates that the necessary modifications detected by the 2to3 fixers
will be written directly to the python2to3.py file