# DeepWeeds : A Multiclass Weed Species Classification Using Deep Learning

<br>

## Summary

The project is a multiclass weed species classification model build using deep learning algorithms. our model power weed control robots to control weed species in farms to boost productivity and personalize the fertilizers.

## Dataset 
The dataset used in this project is the DeepWeed provided by [DeepWeeds: A Multiclass Weed Species Image Dataset for Deep Learning](https://www.nature.com/articles/s41598%20018%2038343%203) paper which consists of 17,509 labelled images of eight nationally significant weed species native to eight locations across northern Australia.


## Model Architecture
The convolutional neural network architecture that we use to perform this task of multiclass weed species classification is [ResNet](https://arxiv.org/abs/1605.07146) that already implemented in Keras high-level API of TensorFlow.


## Dependencies
- Python 3.7 64bit
- Windows 10 64 bit / version 1909
- Nvidia Geforce RTX 2060 laptop
- cuda_11.0.2_451.48_win10
- cudnn-11.0-windows-x64-v8.0.1.13
- Bazel 3.1.0

## Recommended
Note that is better to create a new virtual environment and install requirements in it to isolate your project from your default environment and to avoid all problems that caused by version conflict.
- The first think is to install ``virtualenv``.
- ``` 
  pip install virtualenv
  ```
- Clone the project
- ```
    cd deepweeds_computervision
  ```
  Now the folder venv is you main environment and you can name it what are every you want. and all the packages you will install it will store there.
- ```
    virtualenv \venv
  ```
    To activate your virtual environment.
- ```
    venv\Scripts\activate.bat
  ```
  Now you can install any python packages you want in the command line that you are activating the virtual environment and they will be isolated.

  To exit the virtual environment. 
- ```
    deactivate
  ```
  For more information check [her](https://www.datacamp.com/community/tutorials/virtual-environment-in-python).


## Requirements
- Get the package from PyPi.
- All requirements that you will need with its version it's exist in [requirements.txt](/requirements.txt) so you need just to run this command to install it all :
   ```
   !pip install -r requirements.txt
   ```
- Download the pre-trained weight [here](https://drive.google.com/file/d/1yukW03-cSyICnoyD9astn4EdeaAEJFBF/view?usp=sharing) then add it to `\Checkpoint` folder.

## How to run it
When you install all requirements pick in the repository and make sure to activate your virtual environment then start ``jupyter lab`` environment.
   ```
   jupyter lab
   ```
Then open the browser and tap [``http://localhost:8888/lab``](http://localhost:8888/lab) and do the heck you want with it.


## Training the model
Note in the notebook we add a clause to test if the model already exists in the path `\Checkpoint` before we create and compile a new one so that we launch training many times for a small number of epochs.

You don't need to download the pre-trained weight if you want to retrain the model from the beginning.


## Authors
* [Abdelati Elasri](https://github.com/iElasri)
* [El Houcine ES SANHAJI](https://github.com/essanhaji)


## Thank you.
