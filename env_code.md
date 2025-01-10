# Create a new conda environment named 'dl-env' with Python 3.10
conda create -n dl-env python=3.10

# Activate the new environment
conda activate dl-env

# Install the required packages
conda install pandas scikit-learn matplotlib numpy

# Install TensorFlow using pip
pip install tensorflow

# Install PyTorch and torchvision for CPU only
conda install pytorch torchvision torchaudio cpuonly -c pytorch

# Install skorch
pip install skorch

# Install pytorch-tabnet
pip install pytorch-tabnet