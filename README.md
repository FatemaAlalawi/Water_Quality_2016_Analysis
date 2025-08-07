
**Decoding the Flow**

## Description

 Analysis of water quality validation for an online anomaly detection system output was performed. Tha main objectives of this analysis is providing a trust that water is safe for drinking at both normal and change detection datasets, visualizing parameter trends over time, and exploring Parameter relationships through correlation analysis. 
## Dataset

The dataset used for this analysis is provided by Online Anomaly Detection system for Drinking Water Quality at the Genetic and Evolutionary Computation Conference 2018, Kyoto, Japan, 2018 . It includes time series data of water flow rate, temperature and quality indicators (pH, chlorine dioxide concentration, turbidity, redox potential, and electrical conductivity.
https://zenodo.org/records/3884398

## Analysis

we found out that water is safe for drinking and within the recommeded standards provided py WHO for both normal and change detection datasets. the trends of water quality parameters with time was increasing, decreasing, or falcutating with no clear trend, beacuse of defferent factors affected each parameter. Some parameters was related to each othe while others are not even chemically it should be, this probably caused by either inaccurate sensors readings or presence of other materials that affected it and changed it is behavior. 

## Dependencies
1- Pandas
2- Matplotlib.pyplot
