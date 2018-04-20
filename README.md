# MosquitoCNN

Open a terminal client.

Enter conda -V into the terminal command line and press enter.

If conda is installed you should see somehting like the following.

$ conda -V
conda 3.7.0

In the terminal client enter
$ conda update conda

Upadate any packages if necessary by typing y to proceed.

In the terminal client enter the following where yourenvname is the name you want to call your environment, and replace x.x with the Python version you wish to use. (To see a list of available python versions first, type conda search "^python$" and press enter.)

$ conda create -n PI2 python=3.5 anaconda

Press y to proceed. This will install the Python version and all the associated anaconda packaged libraries at “path_to_your_anaconda_location/anaconda/envs/PI2"

To activate or switch into your virtual environment, simply type the following where yourenvname is the name you gave to your environement at creation.
source activate yourenvname
Activating a conda environment modifies the PATH and shell variables to point to the specific isolated Python set-up you created. The command prompt will change to indicate which conda environemnt you are currently in by prepending (yourenvname). To see a list of all your environments, use the command conda info -e.

$ conda install -c anaconda scipy 
