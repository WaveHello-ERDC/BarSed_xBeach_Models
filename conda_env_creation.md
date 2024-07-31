## Instructions to create Conda env and load all of the packages Jonathan used

Purpose: The purpose of these instructions is to walk the user through the process of setting up a conda environment that has all of the necessary packages to run the scripts that do the xBeach model generation and analysis.

The instructions assume you have conda installed and have access to it in the terminal

1) Create a new enviroment with the python version that Jonathan used. Other python versions may work but they haven't been tested. 

**Note**: Replace "new_env_name" with the desired name of the environment
    ```
    conda create --name new_env_name  python=3.12.3
    ```

2) Activate the new environment
    ```
    conda activate new_env_name
    ```
3) Make sure that the ```environment.yaml``` file is in the directory your conda terminal is in.

4) Run 
    ```conda env create --file environment.yaml```