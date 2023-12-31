# Fall 2023 Practicum

## Project Setup Instructions 

##### This is based on MacOS. See respective links below for downloading git and conda. Please Slack @Deborah Chang if you have any issues with opening the code file.
##### Git: https://macpaw.com/how-to/install-git-mac#:~:text=Before%20you%20install%20Git%20from,Press%20Return.
##### Conda: https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html or https://www.anaconda.com/download
##### Jupyter: https://anaconda.org/anaconda/jupyter

Steps:

1. Clone this repository using this command `git clone https://github.com/d8chang/fa23-practicum` in the Terminal.
2. Within the repository directory, unzip package.zip using this command: `unzip package.zip`
3. The files: README.md, Practicum Code.ipynb, environment.yml, training_data.xlsx, test_data.csv, eda.txt, and deborah_chang_predictions.pkl should now be present in the repo. For the README and pickle file, since a copy of each are already in the repo, feel free to rename/replace them with the ones in the zip file.  
4. Create the environment with the following command: `conda create -n environment.yml` Proceed with updating conda if it asks you to.
5. Activate the environment with this command: `conda activate environment.yml`
6. Install Jupyter using this command: `conda install jupyter` Proceed with installing packages if asked.
7. Apply the command: `jupyter notebook`
8. A localhost page should automatically open with all the files in the repo. Select "Practicum Code.ipynb" to get to the jupyter notebook.

Note: If the commands for setting up the environment or jupyter do not work, try adding "sudo" in front of the command. See [this article](https://docs.conda.io/projects/conda/en/4.6.0/user-guide/tasks/manage-environments.html#activating-an-environment) for reference.
