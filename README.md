# Python_Pandas_Lessons

This repository includes introduction to Python and Pandas. 

Python is a high-level, general-purpose programming language. Created by Guido van Rossum in 1989 as a scripting language for administrative tasks; it was named after a television show. First released in 1991. There has been a growing community of Python developers since then, evolving into a well-supported programming language. Python 3.0, released in 2008, was a significant revision of the language. Python has become a common programming language for machine learning and the primary language for TensorFlow. The Python Software Foundation (PSF), a non-profit organization, manages for Python development. See Python website at [www.python.org](https://www.python.org/)

Pandas is an open source Python package for data manipulation and analysis with high-performance and easy-to-use methods. It is based on the dataframe concept in the R programming language. Pandas can be used as the primary tools for data processing, data manipulation and data cleaning.


# Installing Python

Anaconda distribution of Python is recommended since it already contains many data science packages. Anaconda is free (the download is large and take time) and can be installed on work or school or personal computers. Anaconda comes bundled with about pre-installed 600 packages. Download the latest version of Python 3 (As of August 2020, 3.8) from [Anaconda.com/downloads](https://www.anaconda.com/products/individual) and install it on your computer (only press next).

<p>&nbsp;</p>
<img src="https://raw.githubusercontent.com/MehdiRezvandehy/Machine-Learning-Course-University-of-Calgary/master/Images/Fig2-1.png " alt="drawing" width="900"/>
<p>&nbsp;</p>

## Installing Jupyter and Required Modules

The Jupyter notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Jupyter Notebooks Allow Python and Markdown to coexist. We can write LaTeX equation in Jupyter notebook.

Jupyter notebooks will be frequently used in this course. It should be installed into your base Python environment. Go to Windows Start menu, type *Anaconda Prompt (Anaconda3)*, right click on that and select *Run as administrator* to launch the anaconda console (see Figure below).
Check to see if pip (pip is a package manager for Python packages, or modules) is installed by typing this command in the anaconda console and press enter: **pip3 --version**

<p>&nbsp;</p>
<img src="https://raw.githubusercontent.com/MehdiRezvandehy/Machine-Learning-Course-University-of-Calgary/master/Images/Fig2-2.png " alt="drawing" width="650"/>
<p>&nbsp;</p>

Make sure that you have a recent version of pip installed. To upgrade the pip module, type this command in the anaconda console and press enter: **pip3 install --upgrade pip** 

Now install and upgrade all required modules and their dependencies by typing this command in the anaconda console:
**pip3 install --upgrade jupyter matplotlib numpy pandas scipy scikit-learn**

It may take a few minutes to complete. Try to import every module to check installation:

**python -c "import jupyter, matplotlib, numpy, pandas, scipy, sklearn"**

There should be no error and no output in console after pressing enter.


## Launch Jupyter Notebook in a Specific Folder

If you want to launch a new or previously saved notebook in a specific directory, go to Windows Start menu and type *Anaconda Prompt (Anaconda3)* to launch the anaconda console: you can pin Anaconda Prompt to taskbar (see Figure below).


Then, if you want to change drive type this command: drive name:. For example, if you want to go from drive C to F, type **F:** (see Figure below). Then, if you want to a folder, type **cd** folder's name. For example, Figure below shows how to launch a new notebook in drive F, folder Python.

<p>&nbsp;</p>
<img src="https://raw.githubusercontent.com/MehdiRezvandehy/Machine-Learning-Course-University-of-Calgary/master/Images/Fig2-4.png " alt="drawing" width="900"/>
<p>&nbsp;</p>
