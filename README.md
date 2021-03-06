# MODIS-Aggregation
[![Binder](https://binder.pangeo.io/badge.svg)](https://binder.pangeo.io/v2/gh/big-data-lab-umbc/MODIS-Aggregation/master)

# Master Branch Build Status
[![Build Status](https://travis-ci.org/big-data-lab-umbc/MODIS_Aggregation.svg?branch=master)](https://travis-ci.org/big-data-lab-umbc/MODIS_Aggregation)

# Documentation
Read the documentation online at: http://modis-aggregation.rtfd.io

### Installation
#### Conda environment setup
```
conda create -n MODIS_Aggregation -c conda-forge python=3.7 libnetcdf netCDF4 netCDF4 dask distributed xarray h5py

>> git clone https://github.com/big-data-lab-umbc/MODIS_Aggregation.git
>> cd MODIS
>> python setup.py install
```

The code is tested with Python 3.7

# Team members
- PI: [Dr. Jianwu Wang](https://userpages.umbc.edu/~jianwu/), Department of Information Systems, UMBC
- Co-I: [Dr. Zhibo Zhang](https://physics.umbc.edu/people/faculty/zhang/), Department of Physics, UMBC
- Co-I: Steven Platnick, NASA Goddard Space Flight Center
- Co-I: Kerry Meyer, NASA Goddard Space Flight Center
- Developer: Gala Wind, NASA Goddard Space Flight Center
- Developer: Paul Hubanks, NASA Goddard Space Flight Center
- PhD student: Jianyu Zheng, Department of Physics, UMBC
- PhD student: Chamara Rajapakshe, Department of Physics, UMBC
- PhD student: Pei Guo, Department of Information Systems, UMBC
- PhD student: Redwan Walid, Department of Information Systems, UMBC
- MS student: [Savio Kay](https://saviokay.com), Department of Information Systems, UMBC
- MS student: Deepak Prakash, Department of Information Systems, UMBC
- MS student: Lakshmi Priyanka Kandoor, Department of Information Systems, UMBC

# Publications
- Jianwu Wang, Xin Huang, Jianyu Zheng, Chamara Rajapakshe, Savio Kay, Lakshmi Kandoor, Thomas Maxwell, Zhibo Zhang. Scalable Aggregation Service for Satellite Remote Sensing Data. In Proceedings of the 20th International Conference on Algorithms and Architectures for Parallel Processing (ICA3PP 2020), pages 184-199, Springer, 2020. 

# Acknowledgement
The project is mainly funded by NASA CMAC program
