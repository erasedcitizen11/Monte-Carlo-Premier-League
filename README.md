# Monte Carlo Simulation of the 2021-2022 English Premier League (and beyond)
## Purpose
Simulates the results of the English Premier League for a number of seasons forward (specified by the user).
## Installation (Pre-requisites)
This project uses the Anaconda distribution of Python so the user must first install Anaconda prior to running any scripts.
Please visit https://docs.anaconda.com/anaconda/install/index.html for instructions to install the latest version of Anaconda. Anaconda is supported on 
Windows, macOS and Linux with separate installation instructions available for each of these operating systems. The user should select the latest version of Python 3
corresponding to their operating system.

The script for this project was written using the Jupyter Notebook editor on Anaconda. This is a specific IDE (Integrated Development Editor) that comes with the Anaconda distribution. Note that files written in
Jupyter Notebook have a unique format compared with other .py files (Jupyter files have the extension .ipynb) so they cannot be opened with any other Python editor (e.g PyCharm). Therefore, the user **must** use Jupyter Notebook to run the scripts. Once Anaconda
has been installed the user can load the Jupyter Notebook editor by following instructions at https://jupyter.readthedocs.io/en/latest/running.html

Note that the user need not install any additional Python packages as all packages used for this project come with the Anaconda distribution of Python.

Once Jupyter Notebook is up and running, the user is ready to run the program.

## Running the program
The entire program is executed within *'MC_project.ipynb'*, the only Python script on the repository. Alongside *'MC_project.ipynb'* are three additional files: *'mc_res_backtest.pickle'*, *'mc_res_oneseason.pickle'* and *'mc_res_10seasons.pickle'*. These files contain the simulations (data) for the three Monte Carlo simulations that were run as part of the project and were the basis for the analysis contained within the report. The main script *'MC_project.ipynb'* will load these data into Python which the user can then analyse. **Therefore, the user needs to download *'MC_project.ipynb'* plus the three data files and ensure all files are in the same directory for the program to run properly**.

Using Jupyter Notebook, the user should load *'MC_project.ipynb'* from where they have this file saved in their directory. This Jupyter file is setup such that the user execute each cell sequentially rather than executing the entire program in one go. For more tips on how to navigate Jupyter Notebook, please visit https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html.


Instructions on how the user can configure the settings for the simulation are detailed in *'MC_project.ipynb'* while all relevant documentation is also included in this file. One last point to note is that this Monte Carlo simulation is very computationally intensive with one iteration taking 30 seconds to complete. The user should bear this mind when selecting the number of iterations to run the simulation.




