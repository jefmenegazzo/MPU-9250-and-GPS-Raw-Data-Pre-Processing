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

This project preprocesses the raw data sampled through MPU-9250 and GPS.

## Table of Contents
- [How To Use](#How-To-Use)
- [How To Cite](#How-To-Cite)

## How To Use

There are four jupyter notebooks and configuration files:

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
