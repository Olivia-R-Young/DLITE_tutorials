To download and use: 

1.) Download the repo as .zip file using "<>Code" Button on the top right corner. 

2.) Unzip folder

3.) Upload unzipped folder to Google Drive. 

4.) Open "DLITE_data_processing_tutorial.ipynb" in Google Colab by clicking on the file in Google Drive.

5.) In the first code block, make sure to change the "%cd /content/drive/My Drive/Colab Notebooks/DLITE" command to match the folder to which you have uploaded the code repo. For example, if the files are in /content/drive/My Drive/DLITE/DLITE_tutorials-main, this command should read: "%cd /content/drive/My Drive/DLITE/DLITE_tutorials-main".


This notebook walks through the creation of Frequency Differences in Arrival/Time Difference in Arrival (FDOA/TDOA) plots for one baseline of a Deployable Low-Band Ionosphere and Transient Experiment (DLITE) array. DLITE is a four-element array that observes below the FM radio band at 35-45 MHz. FDOA/TDOA plots are visibility plots, allowing us to pick out individual bright sources and track their movement. Sources of particular interest at the radio bright A-Team sources (Cygnus A, Cassiopeia A, Virgo A, Taurus A, Hercules A, and Hydra A) and the Sun.

In this notebook, we will use data taken by a DLITE array in Montville, Ohio on the day of the 2024 Total Solar Eclipse. We will construct FDOA/TDOA plots, label the A Team sources and the Sun, and create an animation of the low-frequency radio sky on the day of the eclipse. Additionally, we will plot the intensity of the Sun over the day of the eclipse. Although there is additional processing needed to isolate the Sun for more accurate estimations, the overall behavior of the low-frequency radio solar eclipse can still be seen.

The data are stored in a Google Drive, which you must connect your Google Notebook to. This drive also contains data from the day before and the day after the eclipse.
