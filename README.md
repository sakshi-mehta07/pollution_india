Replicability:

Download the environment.yml and then run the following commands on your terminal:

conda env create -f environment.yml

This should build a conda environment called m_data, if you activate it you should have the right version of all packages to run the main file.

The main file is inside the CODE_INDIA folder "/CODE_INDIA/MAIN_CODE.ipynb"

- If you set the wd at the 2024-project-pollution-team level the code inside the file will work as all paths are relative.
- The main code file calls on DATA_INDIA files to work so you will need to clone the whole repo.
- All code is run in the moment except for the weather api call because it takes some minutes.

STRUCTURE OF DIRECTORY:

CODE_INDIA: Contains the main file and all other files, we split most tasks into separate files and merged them together for the final file. The other files are not clean.

DATA_INDIA: It contains subfolders with the each component of the data, aqi, weather, etc,etc.
