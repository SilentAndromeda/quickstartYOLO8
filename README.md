# Here is a quick example for setting up and running an object detection script in Jupyter Lab using YOLO8, PyTorch, and CUDA

## Git clone this repo

Within git bash, run the following:
```
git clone https://github.com/SilentAndromeda/quickstartYOLO8.git

cd quickstartYOLO8
```

## Set up an Anaconda environment for using Ultralytics-YOLO (you only look once)

Within conda terminal, run the following:
```
conda create --name ultralytics-env python=3.9 -y

conda activate ultralytics-env

conda install -c pytorch -c nvidia -c conda-forge pytorch torchvision pytorch-cuda=11.8 ultralytics

pip install opencv-contrib-python

conda install -c conda-forge jupyterlab

conda install -c conda-forge ipykernel

python -m ipykernel install --user --name=ultralytics-env
```

## Run TestYOLOObjectDetection.ipynb within Jupyter Lab 
`jupyter lab`

![screenshot](AnnotatedVideoFrame.png)
