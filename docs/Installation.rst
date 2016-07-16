============
Installation
============
 
Requirements
------------
    * Python 2.7 or Python 3.3+
    * C or C++ compiler (parts of the package are in Cython for efficiency reasons, and you need C or C++ compiler to compile these parts) 

Platforms
------------
py_stringmatching has been tested on Linux (Ubuntu with Kernel Version 3.13.0-40-generic), OS X (Darwin with Kernel Version 13.4.0), and Windows 8.1.

Dependencies
------------
    * numpy 1.7.0 or higher
    * six

.. note::

     The py_stringmatching installer will automatically install the above required packages.

There are two ways to install py_stringmatching package: using pip or source distribution.

Installing Using pip
--------------------
The easiest way to install the package is to use pip, which will retrieve py_stringmatching from PyPI then install it::

    pip install py_stringmatching
    
Installing from Source Distribution
-------------------------------------
Step 1: Download the py_stringmatching package from `here
<https://sites.google.com/site/anhaidgroup/projects/py_stringmatching>`_.

Step 2: Unzip the package and execute the following command from the package root::

    python setup.py install
    
.. note::

    The above command will try to install py_stringmatching into the defaul Python directory on your machine. If you do not have installation permission for that directory then you can install the package in your home directory as follows::

        python setup.py install --user

    For more information see the StackOverflow `link
    <http://stackoverflow.com/questions/14179941/how-to-install-python-packages-without-root-privileges>`_.
