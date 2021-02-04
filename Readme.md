# Getting Started with Keras

This is a set of instructions on how to use Keras, from setting up the conda environment until getting results from python code with keras.

## How I setup the tensorflow environment

### Creating new environment with Anaconda (conda)

The complete documentation on how we could use conda is here https://docs.anaconda.com/anaconda/user-guide/tasks/tensorflow/

```
conda create -n <folder_name> tensorflow
```

cd into folder

```
conda activate <folder_name>
```

Install your dependencies (tensorflow, keras)

```
pip install tensorflow
pip install keras
```

### Using Jupyter Notebook as Text Editor

https://jupyter.org/install

If you use conda, you can install it with:

```
conda install -c conda-forge jupyterlab
```

If you use pip, you can install it with:

```
pip install jupyterlab
```

If installing using pip install --user, you must add the user-level bin directory to your PATH environment variable in order to launch jupyter lab. If you are using a Unix derivative (FreeBSD, GNU / Linux, OS X), you can achieve this by using export PATH="$HOME/.local/bin:$PATH" command.

Run jupyter lab with

```
jupyter-lab
```

## Use the Documentation

https://keras.io/getting_started/intro_to_keras_for_researchers/
