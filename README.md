
**Decoding the Flow**

## Description
Analysis of water quality validation for the output of an online anomaly detection system was performed. The main objectives of this analysis are providing a trust that water is safe for drinking at both normal and change detection datasets, visualizing parameter trends over time, and exploring parameter relationships through correlation analysis. 

## Dataset
The dataset used for this analysis is provided by the Online Anomaly Detection system for Drinking Water Quality at the Genetic and Evolutionary Computation Conference 2018, Kyoto, Japan, 2018. It includes time series data of water flow rate, temperature, and quality indicators (pH, chlorine dioxide concentration, turbidity, redox potential, and electrical conductivity).
https://zenodo.org/records/3884398

## Analysis
We found out that water is safe for drinking and within the recommended standards provided by WHO for both normal and change detection datasets. The trends of water quality parameters with time were increasing, decreasing, or fluctuating with no clear trend because different factors affected each parameter. Some parameters were related to each other, while others are not even chemically related; they should be. This is probably caused by either inaccurate sensor readings or the presence of other materials that affected it and changed itsbehavior. 

## Conclusion
The analytical process confirms the water is safe for drinking despite the presence of some anomalous changes, providing crucial insights that ensure public confidence in a vital resource. Furthermore, our analysis revealed that while some water quality parameters are correlated, others show no correlation, even when it is chemically plausible. This discrepancy suggests either sensor inaccuracies or the presence of other factors influencing the readings.

## Dependencies
Pandas and Matplotlib.pyplot
