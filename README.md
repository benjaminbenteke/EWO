# EWO

To run this code, you will need to download:
- Past data: https://github.com/cdcepi/Flusight-forecast-data.git
- Current data: https://github.com/cdcepi/FluSight-forecast-hub.git, then the name will be: "FluSight-forecast-hub-main"

# Dependency Structure:
Everything has to be in the same folder, for instance:
- Flusight-forecast-data-master
- FluSight-forecast-hub-main
- UGuelphensemble-GRYPHON
- Weights_without_correct
- EWO_Without_Correction.ipynb


Before running, create this folder: UGuelphensemble-GRYPHON/UGuelphensemble-GRYPHON/US/EWO_Without_correct/ and after running everything will be inside.

# Plot1: weights for each horizon

 horizon 0            |  horizon 1 |  horizon 2 |  horizon 3
:--------------:|:--------:|:--------:|:--------:
![](weights0.png)  |  ![](weights1.png) |  ![](weights2.png) |  ![](weights3.png)


# Plot 2: forecasts
 horizon 0            |  horizon 1 |  horizon 2 |  horizon 3
:--------------:|:--------:|:--------:|:--------:
![](EWO0.png)  |  ![](EWO1.png) |  ![](EWO2.png) |  ![](EWO3.png)
