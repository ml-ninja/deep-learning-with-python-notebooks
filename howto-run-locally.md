Instructions for running Jupyter on Ubuntu 18.04
===================================================


One-off Setup
-------------

1. Install Miniconda

   ```
   wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   chmod 755 Miniconda3-latest-Linux-x86_64.sh
   ./Miniconda3-latest-Linux-x86_64.sh 
   source  ~/.bashrc 
   ```

2. Create a virtual environment

   ```
   conda env create -f environment_ubuntu.yml 
   ```


Launching Jupyter locally
--------------------------

Once the above has been set up properly, follow these steps to run Jupyter locally.

1. Activate the virtual environment

   ```
   conda activate ninjaLab
   ```

4. Launch Jupyter notebook
   ```
   jupyter lab
   ```
