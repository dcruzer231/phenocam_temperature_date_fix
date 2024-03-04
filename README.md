# phenocam_temperature_date_fix
Using Phenocam temperature logs to correct timestamps.  

All the codes was written in jupyter notebook with default conda kernel.  The conda_requirements.txt is used to create a conda environment.

## phenocamTemperature.ipynb
The jupyter notebook for using rolling rmse to compare the temperatures logs with historical temperature data.  The output is a csv file of each day in the field season and the time offset calculated for that day.

## phenocamTimeoffsetMatch.ipynb
Using the csv file produced in the first notebook, I use this notebook to match image timestamps and apply the offset.  I then copy the images with the new timestamps in the name.  
