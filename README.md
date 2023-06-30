# Python_to_Siemens_PLC_Connection

# a simple example of communication between PC and PLC via Python with python-snap7 library.
Let’s assume that Python and pip are already installed on your PC.

Let’s install the library. 

```
 pip install python-snap7
```
$

For example, the PLC in the machine has an IP address: 192.168.0.1

To write a simple Python program to connect to the PLC you need to import library 

# Import the library

$ import snap7
$ from snap7 import util
