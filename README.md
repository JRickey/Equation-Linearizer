# Equation-Linearizer
This python notebook allows you to take any mathematical function and separate it into a series of linear functions over a range.

This allows for computational efficiency in calculating values from the function, specifically useful for computationally expensive environments.

The linearize function takes 4 parameters

1) The mathematical function itself, defined as a python function
2) The lower x bound
3) The upper x bound
4) The number of buckets. This number determines how many linear equations are created. More equations means less error.
