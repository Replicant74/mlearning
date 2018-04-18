# mlearning
Machine Learning in Python: Steps 

Installing the Python and SciPy platform. There are 5 key libraries that you will need to install. Below is a list of the Python SciPy libraries required for this tutorial:
- scipy
- numpy
- matplot
- libpandas
- sklearn
The www.scipy.org/install.html page provides instructions for installing the above libraries. 
https://www.macports.org/install.php for MacOS.

The script below will help you test out your environment. 
It imports each library required in this tutorial and prints the version.
Open a command line and start the python interpreter:		 			 
python 

https://machinelearningmastery.com/machine-learning-in-python-step-by-step/
I recommend working directly in the interpreter or writing your scripts and running them on the command line rather than big editors and IDEs. 
Keep things simple and focus on the machine learning not the toolchain.Type or copy and paste the following script:		 			 

# Check the versions of libraries

# Python version
import sys
print('Python: {}'.format(sys.version))
# scipy
import scipy
print('scipy: {}'.format(scipy.__version__))
# numpy
import numpy
print('numpy: {}'.format(numpy.__version__))
# matplotlib
import matplotlib
print('matplotlib: {}'.format(matplotlib.__version__))
# pandas
import pandas
print('pandas: {}'.format(pandas.__version__))
# scikit-learn
import sklearn
print('sklearn: {}'.format(sklearn.__version__))1234567891011121314151617181920# Check the versions of libraries # Python versionimport sysprint('Python: {}'.format(sys.version))# scipyimport scipyprint('scipy: {}'.format(scipy.__version__))# numpyimport numpyprint('numpy: {}'.format(numpy.__version__))# matplotlibimport matplotlibprint('matplotlib: {}'.format(matplotlib.__version__))# pandasimport pandasprint('pandas: {}'.format(pandas.__version__))# scikit-learnimport sklearnprint('sklearn: {}'.format(sklearn.__version__)) 

Here is the output I get on my OS X workstation:		 			

Python: 2.7.11 (default, Mar  1 2016, 18:40:10) 
[GCC 4.2.1 Compatible Apple LLVM 7.0.2 (clang-700.1.81)]
scipy: 0.17.0
numpy: 1.10.4
matplotlib: 1.5.1
pandas: 0.17.1
sklearn: 0.18.

11234567Python: 2.7.11 (default, Mar  1 2016, 18:40:10) [GCC 4.2.1 Compatible Apple LLVM 7.0.2 (clang-700.1.81)]scipy: 0.17.0numpy: 1.10.4matplotlib: 1.5.1pandas: 0.17.1sklearn: 0.18.1

Loading the dataset.
Summarizing the dataset.
Visualizing the dataset.
Evaluating some algorithms.
Making some predictions.

