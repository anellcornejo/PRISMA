# PRISMA
Producing Resolved and Integrated Spectra from siMulated gAlaxies

This repository includes a Jupyter notebook that shows how to generate synthetic spectra using PRISMA.

**To run this tutorial, follow these steps:**

   1. **Create a Conda environment to work with PRISMA**
	You can install Anaconda from https://www.anaconda.com/download/success. 
	To create a Conda environment with Python 3.9.16, run the following command 
	(this example uses prisma_py3.9 as the environment name)

	conda create -n pprisma_py3.9 python=3.9.16


2- **Activate the environment:**

	conda activate prisma_py3.9


3- **Install CIGALE** by following the step-by-step installation 
   guide available at: https://cigale.lam.fr/documentation/

4- **Install additional dependencies with pip:**

	pip install jupyter pandas pytest-shutil shapely 

   
5- **Navigate to the PRISMA directory and run the notebook** PRISMA.ipynb 
    using the data provided in the Data_sims/ folder.
