biobankAccelerometerAnalysis
======================

A tool to extract meaningful health information from large accelerometer
datasets e.g. how much time individuals spend in sleep, sedentary behaviour,
and physical activity.

This software will allow non-specialists worldwide to benefit from the
information currently locked within the accelerometer data of large health
studies e.g. UK Biobank are asking 100,000 people to wear wrist-worn
accelerometers for 1 week each, and will then monitor their health for the
rest of their lives.


<h2>Usage</h2>
To extract a summary of movement (average sample vector magnitude) and
(non)wear time from raw GENEActiv/Axivity .bin/.CWA accelerometer files 
([click here for sample CWA file]
(http://users.fmrib.ox.ac.uk/~adoherty/CWA-DATA.CWA)):

```
python ActivitySummaryFromEpochs.py [input_file.CWA] [options]
python ActivitySummaryFromEpochs.py p001.cwa
```

For customised options, please refer to our wiki.


<h2>Installation</h2>
Dependancies include: matlab, java, and python (numpy and pandas).
```
javac *.java
```


<h2>Under the hood</h2>
We are using a combination of published methods to extract meaningful health
information from accelerometer data. For more information, please refer to our
wiki.

![Accelerometer data processing overview]
(http://users.fmrib.ox.ac.uk/~adoherty/accProcessingOverview.png)


<h6>Licence</h6>
This project is released under a BSD Licence (see LICENCE)
