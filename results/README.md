# Results

The outputs of the script **Bird_detection_and_time_serie_from_AudioMoths_BirdNET.ipynb** were stored as results with the following structure:

```
├── results
   ├── Birds_detected
      ├── field_sp.txt
      ├── forestending_sp.txt
      ├── residentialarea_sp.txt
      ├── riverside_sp.txt
   ├── Birds_detected_time_serie
      ├── field.html
      ├── forestending.html
      ├── riverside.html
      ├── urban.html
     
```

The .txt files in Birds_detected folder contain dictionaries with:

 - common_name: common name of the bird specie detected  
 - scientific_name:  scientific name of bird detected
 - start_time:   start time in the 10 minutes audio used to detect species using BirdNET (seconds)
 - end_time: start time in the 10 minutes audio used to detect species using BirdNET (seconds)
 - confidence: confidence of BirdNET neural network regarding the detected specie (0-1)
 - date_time: day and time where the specie was detected (mm-dd-yyyy %HH:%MM:%SS)

The .html files in Birds_detected_time_serie folder contain interactive plots with time series of each plot at hourly basis.

![Riverside time serie plot as example.](https://github.com/LRiveroIribarne/IDV_RSGIC_BBOXGroup1/blob/324290205e0294124651a36e862ca30a048dd2c4/imgs/time_serie_example.png)
