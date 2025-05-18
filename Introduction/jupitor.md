## Prequisite step
you have installed python and pip in your computer.

## Step 1. in the terminal window, install Jupyter using the following command:
brew install jupyterlab

## Step 2. in a terminal window, create a Python virtual environment using the following command:
python3 -m venv <venv_name>

## Step 3. Next, activate this new envirnment:
source new_graf_venv/bin/activate

## Step 4.  Install Required Packages in the Virtual Env

pip install ipykernel

## Step 5. Add the Environment to Jupyter as a Kernel
python -m ipykernel install --user --name=test --display-name "Python (test)"

## Step 6. finally, create a new kernel to leverage the virtual environment from jupitor:
ipython kernel install --user --name=<new_kernel_name>

## Step 7. Open VS code and download the Jupyter extension

## Step 8. Open this notebook: introduction/lesson1.ipynb

## Step 7. Execute the first cell by clickingit and hitting shift + return. It should prompt you to select a kernel. Select the kernel created in step 6




