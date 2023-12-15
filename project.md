# Shripriti_project1

Exploring Arrays and Statistics with NumPy in Python
NumPy is a fundamental library for scientific computing in Python, providing powerful tools for creating and manipulating multi-dimensional arrays. Let's delve into its capabilities by creating 1D, 2D, and 3D arrays, and calculating their statistical measures like mean, mode, median, and standard deviation. This exploration can serve as a valuable contribution to your GitHub repository, showcasing your deep understanding of NumPy.

 1. Creating Arrays:

1D Array:

  import numpy as np

  # Create a 1D array with integers
  arr1 = np.array([1, 2, 3, 4, 5])

  # Print the array
  print("1D Array:", arr1)

2D Array:

  # Create a 2D array with random values
  arr2 = np.random.rand(3, 4)

  # Print the array
  print("\n2D Array:")
  print(arr2)


3D Array :

  # Create a 3D array with random values
  arr3 = np.random.rand(2, 3, 4)

  # Print the array
  print("\n3D Array:")
  print(arr3)


2. Calculating Statistics:

Once you have the arrays, you can use NumPy functions to calculate their statistical measures:

Mean:
  # Mean of 1D array
  mean_1d = np.mean(arr1)

  # Mean of 2D array (across all elements)
  mean_2d_all = np.mean(arr2)
  
  # Mean of 2D array (along specific axis)
  mean_2d_axis0 = np.mean(arr2, axis=0)  # Mean of each row

  # Mean of 3D array (across all elements)
  mean_3d_all = np.mean(arr3)

Median:

  # Median of 1D array
  median_1d = np.median(arr1)

  # Median of 2D array (across all elements)
  median_2d_all = np.median(arr2)

  # Median of 2D array (along specific axis)
  median_2d_axis0 = np.median(arr2, axis=0)  # Median of each row

  # Median of 3D array (across all elements)
  median_3d_all = np.median(arr3)


Mode :

  # Mode of 1D array
  mode_1d = np.mode(arr1)

  # Mode is not defined for multi-dimensional arrays
  mode_2d = np.nan

  # You can use custom functions for multi-dimensional mode calculation



3. GitHub Contribution:

By including this exploration in my GitHub repository, I wanted to  demonstrate my expertise in:

NumPy array creation: Highlighting different methods for creating 1D, 2D, and 3D arrays.
NumPy statistical functions: Showcasing the usage of mean, mode, median, and std for various array dimensions and axes.
Code explanation and documentation: Providing clear explanations and comments within your code to enhance understanding.
Remember to adapt this code example to your specific context and add further insights or functionalities to make your contribution even more valuable. With a well-structured and documented exploration.
















