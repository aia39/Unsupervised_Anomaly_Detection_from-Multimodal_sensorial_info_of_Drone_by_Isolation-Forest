# Anomaly_Detection-by-Isolation-Forest
Unsupervised anomaly detection is now a days very vital thing in digital world.Anomaly always expected to happen rarely so unsupervised approach is necessary to deal with it.Isolation forest is one of the renowned method to detect anomaly unsupervised manner.Various use of isolation forest is showed in the repository.


## Installation
1. Clone this repository
2. Install dependencies
   ```bash
   pip install keras
   pip install pandas
   pip install sklearn
   pip install scikit-learn==0.21.2
   pip install pickle-mixin
   ```

## Getting Started 
* [inference.py](inference.py) is the main inference code to run anomaly detection on csv file of IMU data/desired input data.

* [isofor_test.py](isofor_test.py) It is helper function file to run inference.py.It contains the function of multivariate and univariate isolation forest respectively as ' isolation_forest_score() ' and ' univariate_score() '

* [findsensor.py](findsensor.py) It is also a helper function file to run inference.py.It contains the function of to find the top responsible features that causing anomaly in anomalous sample.



