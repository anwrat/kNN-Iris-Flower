# kNN-Iris-Flower

For resolving issues with jupyter notebook<br>
https://www.geeksforgeeks.org/how-to-fix-jupyter-command-not-found-error-after-installing-with-pip/
<br>

# Virtual environment for jupyter notebook

It is recommended to install and run pip packages and notebook in a virtual environment so that the packages are not lost everytime the kernel is restarted. So here are the steps to do so...<br>
## Creating a virtual environment
* Open terminal from search
* Run the command ```python -m venv myenv```
* Then activate the environment using ```myenv\Scripts\activate```
* Install necessary packages for the environment: <b>Example:</b> ```pip install jupyter pandas```
* Start notebook ```jupyter notebook```

## Changing Jupyter default location
* Find the derfault directory using ```jupyter --config-dir```
* cd to the directory found in first step
* If the jupyter_notebook_config.py file does not exist, create it by running: ```jupyter notebook --generate-config```
* Navigate to the folder and Open the jupyter_notebook_config.py file in a text editor (e.g., Notepad or VS Code)
* Scroll to bottom of file and add ```c.NotebookApp.notebook_dir = r"C:/path to your folder"```
* Save and restart virtual environment and Jupyter




