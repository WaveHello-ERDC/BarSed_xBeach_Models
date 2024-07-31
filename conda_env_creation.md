## Instructions to create Conda env and load all of the packages Jonathan used

Purpose: The purpose of these instructions is to walk the user through the process of setting up a conda environment that has all of the necessary packages to run the scripts that do the xBeach model generation and analysis.

1) Open the conda terminal or any terminal that is capable of running conda commands
2) Move the working directory to the location where the ```environment.yaml``` is
3) Run 
    ```conda env create --file environment.yaml```

    The above command should create the environment, whose default name is ```BarSed``` (If a different name is desired it can be changed at the top of the ```environment.yaml```).