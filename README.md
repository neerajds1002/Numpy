# Numpy

Numpy is a python library which provides efficient data structures for reperesenting a rich varieties of arrays and methods and function to operate the same.


## Data Types

### Basic Numerical Data Types Available in NumPy
| dtype |                  Variants          |              Description               |
|:-----:|:----------------------------------:|:--------------------------------------:|
|  int  |        int8, int16, int32, int64   |               Integers                 |
|  uint |   uint8, uint16, uint32, uint64    |   Unsigned (nonnegative) integers      |
| bool  |                   Bool             |       Boolean (True or False)          |
| float | float16, float32, float64, float128|        Floating-point numbers          |
|complex| complex64, complex128, complex256  | Complex-valued floating-point numbers  |




##  Summary of NumPy Functions for Generating Arrays
|       Function       |                                                                    Name Type of Array                                                                |
|:--------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------:|
|      np.array        |Creates an array for which the elements are given by an array-like object,which, for example, can be a (nested) Python list, a tuple, an iterable     sequence, or another ndarray instance.                                                                                                                                        |
|      np.zeros        |       Creates an array with the specified dimensions and data type that is filledwith zeros.                                                         |
|      np.ones         |Creates an array with the specified dimensions and data type that is filled with ones.                                                                |
|      np.diag         |Creates a diagonal array with specified values along the diagonal and zeros elsewhere.                                                                |
|      np.arange       |Creates an array with evenly spaced values between the specified start,end, and increment values.                                                     |
|     np.linspace      |Creates an array with evenly spaced values between specified start and end values, using a specified number of elements.                              |
|     np.logspace      |Creates an array with values that are logarithmically spaced between the given start and end values.                                                  |
|     np.meshgrid      |Generates coordinate matrices (and higher-dimensional coordinate arrays) from one-dimensional coordinate vectors.                                     |
|   np.fromfunction    |Creates an array and fills it with values specified by a given function,which is evaluated for each combination of indices for the given array size.  |
|     np.fromfile      |Creates an array with the data from a binary (or text) file. NumPy also provides a corresponding function np.tofile with which NumPy arrays can be   stored to disk and later read back using np.fromfile.                                                                                                                         |
|np.genfromtxt,np.loadtxt|Create an array from data read from a text file, for example, a commaseparated value (CSV) file. The function np.genfromtxt also supports data     files with missing values.                                                                                                                                                    |
|np.random.rand        |Generates an array with random numbers that are uniformly distributed   between 0 and 1. Other types of distributions are also available in the np.
random module.                                                                                                                                                                |
