# CMSDASLPC2025-Tau-Short-Exercise

### Recommended way to run the exercise (SWAN)

The Tau exercise is organised in two Jupyter notebooks, both contained in this repository.

To run the notebooks with regular CERN resources:
* Open a SWAN session at swan.cern.ch (the defaults are good, as of writing this pick software stack 97a and make sure to use Python3)
* In the SWAN session, click on the item on the right-hand side that says "Download Project from git"
* Copy-paste https://github.com/itzelliss/CMSDASLPC2025-Tau-Short-Exercise.git
* You're all set and can click on the two exercises, `tau_short_exercise_1.ipynb` and `tau_short_exercise_2.ipynb`

### Alternative way to run the exercise

To run the notebooks locally:
* Install [Python](https://www.python.org/downloads/), [ROOT](https://root.cern/install/) and [Jupyter](https://jupyter.org/install)
* Open a terminal and create a working directory
* Download the package by `git clone https://github.com/itzelliss/CMSDASLPC2025-Tau-Short-Exercise.git`
* Enter the package by `cd CMSDASLPC2025-Tau-Short-Exercise`
* Download the input files from LPC node by `scp -r YOURLPCUSERNAME@cmslpc-sl7.fnal.gov:/uscms/home/zfwd666/nobackup/CMSDAS/CMSDASLPC2025-Tau-Short-Exercise/inputFiles .`
* You're all set and can launch the two exercises locally, `jupyter-notebook tau_short_exercise_1.ipynb` and `jupyter-notebook tau_short_exercise_2.ipynb`, which will open the kernel in your browser

Troubleshooting:
* The software stack can be installed with brew and/or pip (root, jupyter, python3) locally.
* If the jupyter notebook cannot find ROOT lib link in your laptop despite the above installations, you can try with `root --notebook tau_short_exercise_1.ipynb` and `root --notebook tau_short_exercise_2.ipynb`.

If you finished the exercise, it would be great to send your feedback to 
isegovia@fnal.gov or the mattermost channel with the information 
whether you were able to successfully tackle the exercise and ideally also with pointers to finished notebooks, 
either linked on github, made available as exported websites or documents, etc. At the 
same time, we'd be very interested in getting specific feedback, suggestions, etc, so we can improve the exercise for future usage.
