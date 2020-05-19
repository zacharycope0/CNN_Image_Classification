# CNN Image Classification
The code builds and trains a Convolutional Neural Network to categorize color images from the CIFAR-10 dataset. You will need to use Jupyter Notebook, Python 2.7 (or Python 2.7 Environment), and Keras with the Theano backend. 

Installation
----------------------
* Clone this repo to your computer.
* Install the following requirements in your terminal:
    * `pip2 install -r requirements.txt`
    * `pip2 install --upgrade --no-deps git+git://github.com/Theano/Theano.git`
    * `pip2 install keras`
keras
* Check that Keras is using the Theano backend.
    * In Python terminal input `import keras`.
    * Response should be: `Using Theano backend`.

Data
----------------------
Data can be downloaded here:
http://www.cs.toronto.edu/~kriz/cifar.html
* Download CIFAR-10 python version.
* Unzip the file so that you are left with a folder titled: cifar-10-batches-py

Jupyter Notebook & CNN
----------------------
Run the notebook and start playing with parameters. With the current parameter settings, the model is getting an accuracy of around 67%. Feel free to make changes in the CNN layers to improve the model. 



