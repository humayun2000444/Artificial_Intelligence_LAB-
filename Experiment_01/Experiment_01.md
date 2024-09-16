# Experiment Name: Introduction to Python and Setting Up Python for AI Development

# Description
Python is a powerful, easy-to-learn programming language that has become one of the top choices for artificial intelligence (AI) and machine learning (ML) development. It offers simplicity and flexibility while providing access to a vast array of libraries and frameworks that make building AI applications easier.

This guide will walk you through setting up Python for AI development, including installing essential libraries like NumPy, Jupyter Notebook, and Pandas.

## Why Use Python for AI Development?

- **Ease of learning**: Python’s syntax is clean and easy to understand.
- **Extensive libraries**: Python comes with a wide range of AI and machine learning libraries such as NumPy, Pandas, TensorFlow, PyTorch, Scikit-learn, and more.
- **Community support**: Python has an active and supportive community that is always contributing to its development.
  
## Prerequisites

- Windows 10/11 OS (this guide is tailored for Windows users).
- Basic knowledge of Python (optional, but helpful).

---
# Source Code
## Step-by-Step Installation Guide 🛠

### 1. Install Python (Latest Version)

Python is the foundation of AI development, and installing the latest version ensures you have access to the newest features.

1. Go to the [official Python website](https://www.python.org/).
2. Click the **Download Python** button. The latest version will be automatically suggested for your system.
3. After the download completes, open the installer and follow the steps (click **Next** through the installation process).
4. Make sure you check the box for **Add Python to PATH**—this step is essential for using Python from the command line.

![image](https://github.com/user-attachments/assets/3740c8b2-76c0-4b88-a026-601f19873bb7)
![image](https://github.com/user-attachments/assets/e153fc60-73ca-430a-a0bd-c4881cad1a20)
![image](https://github.com/user-attachments/assets/6a9e05c8-568d-4a49-8699-543e850b4f72)
![image](https://github.com/user-attachments/assets/6b89bad3-d9d5-451e-aadb-188f9eedcefe)

### 2. Verify Python Installation

Once Python is installed:

1. Press **Win + R**, type `cmd`, and hit **Enter**.
2. In the command prompt, type the following to confirm that Python is installed:

   ```bash
   python -V

![image](https://github.com/user-attachments/assets/1bc5e186-6d06-4173-9236-5d64605de25a)


## Setting Up Jupyter Notebook (For Interactive Coding) 📓
Jupyter Notebook is an open-source tool that provides an interactive environment for writing and running Python code, making it perfect for AI development, data analysis, and visualization.

1. Install Jupyter Notebook by typing the following into the command prompt:
   
      ```bash
   pip install notebook

2. Once installed, launch Jupyter by typing:
   
      ```bash
   jupyter notebook

This will open Jupyter in your default web browser, where you can create and run Python notebooks.
![image](https://github.com/user-attachments/assets/3c95867b-429e-4cf0-8795-170ecbee47cc)
![image](https://github.com/user-attachments/assets/de15bfd3-c8e9-4232-ba3e-fc1c5c08d474)


## Setting Up NumPy (For Numerical Computations) 🧮
NumPy is a core library for scientific computing, particularly useful for handling large, multi-dimensional arrays and matrices.

1. Update pip (Python's package installer) by typing:
   
      ```bash
   python -m pip install --upgrade pip

2. Then install NumPy by running:
   
      ```bash
   pip install numpy
      
3. You can verify that NumPy is installed by starting Python:
   
      ```bash
   python
   import numpy as np

![image](https://github.com/user-attachments/assets/4daaf438-5919-4c7a-95e2-f74c45196797)


## Setting Up Pandas (For Data Manipulation) 🐼
Pandas is an essential library for data manipulation and analysis, widely used in AI and machine learning workflows.

1. After Jupyter Notebook is installed, install Pandas by typing:
   
      ```bash
   pip install pandas

2. Verify Pandas installation by opening Jupyter, creating a new notebook, and running:
   
      ```bash
   import pandas as pd
   print(pd.__version__)

![image](https://github.com/user-attachments/assets/55cdfcb3-4e3b-48a7-ac11-12c33948047f)


# Conclusion 🎉
With Python, NumPy, Jupyter Notebook, and Pandas installed, you’re now set up for AI development. From here, you can start exploring machine learning libraries like 
TensorFlow and PyTorch or dive into data science with Scikit-learn. Python’s flexibility and the power of its libraries make it an ideal language for creating AI models and applications. Happy coding! 💻✨




