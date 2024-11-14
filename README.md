# Overview:
A machine learning project that utilises the FER-2013 dataset to build a model for facial emotions recognition. 
Demonstration of the model is included trough a code logic that starts the front camera of the operating machine and detects a human face (if present) with the help of an already existing face detection model from the OpenCV library.

# Installation Guide:
In order to run the project, a few libraries and tools have to be installed in a particular order to set up the required environment for the program.
The installation steps provided below use the packet manager Anaconda to create a virtual environment for the project. Feel free to replicate the steps with a packet manager of choice.
```
* conda create --name tf-gpu python=3.8
* conda activate tf-gpu
* conda install -c conda-forge tensorflow=2.10 keras
* conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1
* conda install jupyter
* conda install ipykernel
* python -m ipykernel install --user --name=tf-gpu --display-name "TF-GPU"
* conda install -c matplotlib seaborn scipy opencv-python datetime

# For GPU accelleration:
* include the following entry in the "PATH" environment variable (example path): "E:\Anaconda\envs\tf-gpu\Library"
* add new environment variable (example path): "CUDA_HOME" with value - "E:\Anaconda\envs\tf-gpu\Library"
* add new environment variable (example path): "CUDA_PATH" with value - "E:\Anaconda\envs\tf-gpu\Library"
```

# Technologies:
* Tensorflow (Machine learning framework) - https://www.tensorflow.org/
* OpenCV (Computer vision library) - https://opencv.org/
* Kaggle (Free ML Datasets web platform)- https://www.kaggle.com/datasets/msambare/fer2013
* Jupyter Notebook (web based development environment) - https://jupyter.org/
