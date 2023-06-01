# Script

The data analysis was done through one python script (**Bird_detection_and_time_serie_from_AudioMoths_BirdNET.ipynb**).

This script consists in six parts described following:
1.  It loads the BirdNET neural network. Capable to detect bird species using audio (.WAV) data.
2.  The BirdNET is run for each plot using the raw .WAV as input, day of the year and coordinates.
3.  The outputs of the BirdNET are exported in .txt format containing all the species detected, when was detected and the confidence of the algorithm about the detected specie.
4.  The data is loaded and the number of species and number of detection is reported per site.
5.  The data is visualized in a interactive time series plot using plotly library displaying the number of birds per specie per hour of the day and site.
6.  Finally, the interactive plots are exported in .html format.