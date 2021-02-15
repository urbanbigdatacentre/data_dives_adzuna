![logo](./images/ubdc_logo.png)

# Intro to geospatial analysis using Python

This is repo containing materials for masters lab


The lab is going to be run in jupyter notebook

## Lab requirements

Please create new environmet for this lab using  **Python 3.7**
 
Using [Anaconda](https://docs.anaconda.com/anaconda/install/)  please install the following 

```python

#Create new environment

conda create --name myenv python=3.7

#Make sure that you are going to work in newly created environment

conda activate myenv

# Install jupyter lab
conda install jupyterlab -c conda-forge

# Install packages
conda install -c conda-forge geopandas
conda install -c conda-forge matplotlib
conda install -c conda-forge mapclassify
conda install -c conda-forge contextily
conda install -c conda-forge pyarrow
conda install -c conda-forge geoplot
conda install -c conda-forge seaborn
conda install -c conda-forge descartes 


#Alternatively run the installation in one line

conda install -c conda-forge jupyterlab matplotlib mapclassify contextily pyarrow geoplot seaborn descartes 

#Start the  jupyter lab

jupyter lab

```
