<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Packages</title>
</head>
<body>
<h1><b><u>PYTHON PACKAGES</u></b></h1>
<h2><b>MODULES</b></h2>
<hr>
<img src="">
<p>
	In this article, you'll learn to divide your code base into clean, efficient modules using Python packages. Also, you'll learn to import and use your own or third party packages in a Python program.
</p>
<ul>
    <li>What are packages?</li>
    <li>A Simple Example</li>
    <li>Importing Module from a Package</li>
    <li></li>
 </ul> 
 <h2>What are packages</h2>
 <p>
 	We don't usually store all of our files on our computer in the same location. We use a well-organized hierarchy of directories for easier access.
    As our application program grows larger in size with a lot of modules, we place similar modules in one package and different modules in different packages. This makes a project (program) easy to manage and conceptually clear. 
    Similarly, as a directory can contain subdirectories and files, a Python package can have sub-packages and modules.

    A directory must contain a file named __init__.py in order for Python to consider it as a package. This file can be left empty but we generally place the initialization code for that package in this file.	
</p>
<h2>A Simple Example</h2>
<p>
  Here is an example. Suppose we are developing a game. One possible organization of packages and modules could be as shown:

  <img src="https://cdn.programiz.com/sites/tutorial2program/files/PackageModuleStructure.jpg">
 </p>
 <h2>Importing Module from a Package</h2>
 We can import modules from packages using the dot (.) operator.

 For example, if we want to import the start module in the above example, it can be done as follows:
               import Game.Level.start
 Now, if this module contains a function named select_difficulty(), we must use the full name to reference it.
                   Game.Level.start.select_difficulty(2) 
 <h2>Few python packages:</h2>
There are more than 200,000 Python packages in the world .
<br>
<p>
<b>1 NumPy</b>
You can do basic mathematical operations without any special Python packages. However, if you’re going to do any kind of complex math, the NumPy package will make your coding life much easier.

NumPy provides tools to help build multi-dimensional arrays and perform calculations on the data stored in them. You can solve algebraic formulas, perform common statistical operations, and much more.

While NumPy is a valuable Python package for a variety of general-purpose programming tasks, it’s particularly important if you want to do machine learning, since it provides part of the foundation for libraries like TensorFlow.

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT73UdNXRozWJh1Q7S-gv3g726OPmJOTW3N8A&usqp=CAU">
<br>
</p>
<br>
<p>
<b>2 SciPy</b>
 
As the name suggests, SciPy is mainly used for its scientific functions and mathematical functions derived from NumPy. Some useful functions which this library provides are stats functions, optimization functions, and signal processing functions. To solve differential equations and provide optimization, it includes functions for computing integrals numerically. Some of the applications which make SciPy important are:

Multi-dimensional image processing
Ability to solve Fourier transforms, and differential equations
Due to its optimized algorithms, it can do linear algebra computations very robustly and efficiently
</p>
<br>
<p>
<b>3 Python Imaging Library</b>
If your Python application interacts with images in any way, the Python imaging library, also known as PIL or Pillow, is a Python must-have. It makes it easy to write code that opens, modifies, and saves images in a variety of formats.

If you’re doing more advanced work with images (like image recognition, in which case OpenCV would be a good package to consider), Pillow won’t cut it on its own. But for basic image importing, manipulation, and exporting, Pillow is your go-to solution.
 </p>                              
<b>4 MoviePy</b>
MoviePy is to videos what Pillow is to images. It provides a range of functionality for common tasks associated with importing, modifying, and exporting video files. It also lets you do things like insert titles into videos or rotate videos 90 degrees (if for some reason you decide you want to do that).

Like Pillow, MoviePy is not intended as a tool for advanced data manipulation. If you’re writing a video editing app, you’ll probably also need to rely on OpenCV (which can work with videos as well as images) to provide the advanced functionality that MoviePy lacks. But for most standard tasks involving videos in Python code, MoviePy gets the job done quite well.

                               


</body>
</html>