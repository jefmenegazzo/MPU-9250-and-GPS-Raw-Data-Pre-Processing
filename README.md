[![GitHub](https://img.shields.io/github/license/Intelligent-Vehicle-Perception/MPU-9250-Data-Plot-Video-Creator)](LICENSE) 
![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/Intelligent-Vehicle-Perception/MPU-9250-Data-Plot-Video-Creator) 
![pypi](https://img.shields.io/pypi/v/pybadges.svg)
![versions](https://img.shields.io/pypi/pyversions/pybadges.svg)
![GitHub issues](https://img.shields.io/github/issues/Intelligent-Vehicle-Perception/MPU-9250-Data-Plot-Video-Creator) 

# MPU-9250 and GPS Raw Data Pre-Processing

This project preprocesses the raw data sampled through MPU-9250 and GPS. For this purpose, there are four jupyter notebooks and configuration files:

- **1 - Raw Data Fix Correction**: In this notebook data collected on the right and left of the vehicle are adjusted and joined with GPS data.
    - *1 - Raw Data Fix Correction.ipynb*: codes that perform operations based on the information in the respective *.py* file.
    - *1 - Raw Data Fix Correction.py*: folder settings to read/write datasets and shift data.

- **2 - Processed Data Visualization**: In this notebook data is shown in graphs.
    - *2 - Processed Data Visualization.ipynb*: code that plots the graphs.
    - *2 - Processed Data Visualization.py*: folder to read datasets.

- **3 - Data Labeling**: this notebook labels the data.
    - *3 - Data Labeling.ipynb*: code that labels the data.
    - *3 - Data Labeling.py*: specification for each label name dataset and sample number that marks the beginning and end of the label.

- **4 - Processed Labels Visualization**: In this notebook data with labels is shown in graphs.
    - *4 - Processed Labels Visualization.ipynb*: code that plots the graphs.
    - *4 - Processed Labels Visualization.py*: folder to read datasets and labels.

For each of the functionalities, just configure the parameters in the .py files and run the jupyter notebook (.ipynb).