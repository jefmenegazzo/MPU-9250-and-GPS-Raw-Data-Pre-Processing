[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://img.shields.io/badge/Project_Status-Active-green?style=flat-square&color=success)](https://github.com/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=flat-square&color=success)](https://github.com/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing)
[![GitHub](https://img.shields.io/github/license/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing?style=flat-square&color=success)](LICENSE)
![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing?style=flat-square) 
![pypi](https://img.shields.io/pypi/v/pybadges.svg?style=flat-square)
![versions](https://img.shields.io/pypi/pyversions/pybadges.svg?style=flat-square)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.3960621-blue?style=flat-square)](https://doi.org/10.5281/zenodo.3960621)
[![GitHub issues](https://img.shields.io/github/issues/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing?style=flat-square)](https://github.com/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing/issues)
[![GitHub forks](https://img.shields.io/github/forks/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing?style=flat-square)](https://github.com/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing/network/members)
[![GitHub stars](https://img.shields.io/github/stars/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing?style=flat-square)](https://github.com/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing/stargazers)
[![GitHub watchers](https://img.shields.io/github/watchers/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing?style=flat-square)](https://github.com/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing/watchers)
[![GitHub contributors](https://img.shields.io/github/contributors/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing?style=flat-square&color=success)](https://github.com/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing/graphs/contributors/)
[![HitCount](http://hits.dwyl.io/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing/badges.svg)](https://github.com/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing)

# MPU-9250 and GPS Raw Data Pre-Processing

This project pre-processes the raw data sampled through MPU-9250 sensors (accelerometer, gyroscope, magnetometer and temperature) and GPS.

## Table of Contents
- [Instalation](#Instalation)
- [How To Use](#How-To-Use)
- [How To Cite](#How-To-Cite)

## Instalation
 
Clone this repository:

```bash
git clone https://github.com/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing.git
```

## How To Use

There are four jupyter notebooks and python configuration files:

- **1 - Raw Data Pre-Processing**: data collected on the right and left side of the vehicle are adjusted, synced and joined with the GPS data.
    - *1 - Raw Data Pre-Processing.ipynb*: jupyter notebook that perform operations described above using the information described in the respective *.py* file.
    - *1 - Raw Data Pre-Processing.py*: configuration file to describe the folder to read/write datasets and time shift data.

- **2 - Pre-Processed Data Visualization**: plot pre-processed data in several graphs.
    - *2 - Pre-Processed Data Visualization.ipynb*: jupyter notebook that plot the data.
    - *2 - Pre-Processed Data Visualization.py*: configuration file to describe the folder to read datasets.

- **3 - Data Labeling**: create labels for data classes.
    - *3 - Data Labeling.ipynb*: jupyter notebook that labels the data.
    - *3 - Data Labeling.py*: configuration file that specifies for each dataset its data class labels and the sample range of the label.

- **4 - Data Labeled Visualization**: plot the data and labels in several graphs.
    - *4 - Data Labeled Visualization.ipynb*: jupyter notebook that plot the data and labels.
    - *4 - Data Labeled Visualization.py*: configuration file to describe the folder to read datasets and labels.

For each of the functionalities, just configure the parameters in the python file (.py) and run the corresponding jupyter notebook (.ipynb).

## How To Cite

To cite this repository, use the reference below:

```bibtex
@software{menegazzo3960621,
    author = {Jeferson Menegazzo and Aldo von Wangenheim},
    title = {{MPU-9250 and GPS Raw Data Pre-Processing}},
    month = jul,
    year = 2020,
    publisher = {Zenodo},
    version = {1.0.4},
    doi = {10.5281/zenodo.3960621},
    url = {https://github.com/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing}
}
```
