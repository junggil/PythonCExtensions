# PythonCExtensions
Using a Python C extension and comparing its performance to NumPy and Python

You need to build the C extension before running this. To build and install the extension run:

```python
python setup.py install
```

stdtest.py has a main method which will compare Python, NumPy and the C extension for small arrays and plot the performance with matplotlib.

*I've modified the wrapper to work both Python 2 and 3.*

## Results
100 ~ 1,000 elements

<img src="https://user-images.githubusercontent.com/1250095/39925817-1b2ae5fa-5568-11e8-9fc9-e2fd57108030.png" width="70%" />

10,000 ~ 30,000 elements

<img src="https://user-images.githubusercontent.com/1250095/39926297-b6c13f36-5569-11e8-9e1a-af74443b536e.png" width="70%" />

## References
- [Speeding up Python and NumPy: C++ing the Way](https://medium.com/coding-with-clarity/speeding-up-python-and-numpy-c-ing-the-way-3b9658ed78f4)
