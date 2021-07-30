# shopping-mah-dudes
groceries exercise
A software program to help ring up purchases made at your grocery store! 

Prerequisites
Anaconda 3.7+
Python 3.7+
Pip
Installation
Fork this remote repository under your own control, then "clone" or download your remote copy onto your local computer.

Then navigate there from the command line (subsequent commands assume you are running them from the local repository's root directory):

cd shopping-mah-dudes
Use Anaconda to create and activate a new virtual environment, perhaps called "my-first-env":

conda create -n my-first-env python=3.8
conda activate my-first-env
After activating the virtual environment, install package dependencies (see the "requirements.txt" file):

pip install -r requirements.txt
NOTE: if this command throws an error like "Could not open requirements file: [Errno 2] No such file or directory", make sure you are running it from the repository's root directory, where the requirements.txt file exists (see the initial cd step above).


Usage
Run the Python script:

python shopping_cart.py


NOTE: if you see an error like "ModuleNotFoundError: No module named '...'", it's because the given package isn't installed, so run the pip command above to ensure that package has been installed into the virtual environment.

Have fun, remember to offer reciepts to all customers! 