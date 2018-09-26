# Detecting and Compensating Sensor Faults in a Hydraulic Condition Monitoring System


Summary of analysis:

+ Used feature extraction of specific "fingerprint" in the cyclical sensor time series data. Feature extraction is an unsupervised process that only depends on the basic shape of the cycle that is to be represented by the elements. 

+ Used dimension reduction technique to deal with the high dimensional problem associated with estimating a vast number of parameters.

+ Performed feature selection, a supervised process that selects the most relevant features concerning a given classification target to reduce further the number of variables that enter into the models.

+ Used LDA, Random Forest, Gradient Boosting models to predict valve condtion and got over 84% and over 99% precision on the potential hazardous end 

+ The result metrics are mainly using three measures:
Accuracy. The percent of data that we accurately predict in each category.
Preicision. The number of true positives divided by the number of true positives plus the number of false positives.
Recall. The number of true positives divided by the number of true positives plus the number of false negatives.


Data: 

UCI Machine Learning dataset: condition monitoring of hydraulic systems Data Set 
https://archive.ics.uci.edu/ml/datasets/Condition+monitoring+of+hydraulic+systems


Data Set Information:

The data set was experimentally obtained with a hydraulic test rig. This test rig consists of a primary working and a secondary cooling-filtration circuit which are connected via the oil tank [1], [2]. The system cyclically repeats constant load cycles (duration 60 seconds) and measures process values such as pressures, volume flows and temperatures while the condition of four hydraulic components (cooler, valve, pump and accumulator) is quantitatively varied.

