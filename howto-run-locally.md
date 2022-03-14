

1. Install Miniconda

   wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   chmod 755 Miniconda3-latest-Linux-x86_64.sh
   ./Miniconda3-latest-Linux-x86_64.sh 
   source  ~/.bashrc 


2. Create virtual environment

   conda env create -f  environment_ubuntu.yml 


3. Activate virtual environment
   conda activate ninjaLab


4. Launch Jupyter notebook
   jupyter  lab


