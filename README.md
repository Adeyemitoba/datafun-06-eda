# datafun-06-eda
Project 6 - EDA Notebook
PROJECT DESCRIPTION
This project aims to demonstrate proficiency in showcasting an exploratory data analysis (EDA) project using GitHub, Git, Jupyter Notebook, pandas, Seaborn. The tools will be used to publish a custom EDA project that tells a compelling data story.

Project Setup
Create Virtual Enviornment
py -m venv .venv
py -m .\.venv\Scripts\activate
Install Dependencies and Upgrade Pip
py -m pip install jupyterlab
py -m pip install pandas
py -m pip install pyarrow
py -m pip install matplotlib
py -m pip install seaborn
py -m pip install --upgrade pip
Freeze Requirements
py -m pip freeze > requirements.txt
Add to gitignore
.venv/
.vscode/
*~
Dependencies Imported
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
import numpy as np
Git Add and Commit
git add .
git commit -m "update message goes here"
git push origin main
