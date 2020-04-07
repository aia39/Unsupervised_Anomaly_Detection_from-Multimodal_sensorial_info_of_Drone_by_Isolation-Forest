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
N.B: To run this code you need to place the training(normal/mostly normal) data csv in the parent directory to increase normal data distribution space.

* [isofor_test.py](isofor_test.py) It is helper function file to run inference.py.It contains the function of multivariate and univariate isolation forest respectively as ' isolation_forest_score() ' and ' univariate_score() '

* [findsensor.py](findsensor.py) It is also a helper function file to run inference.py.It contains the function of to find the top responsible features that causing anomaly in anomalous sample.

* [isofor_Multivariate_Train.py](isofor_Multivariate_Train.py) is the code to train a model using normal data to show the model normal data representation.

* [isofor_train_anomaly_detector_image.py](isofor_train_anomaly_detector_image.py) is the code to train a model using normal image data to show the model normal data representation to isolation forest model.

* [isofor_test_anomaly_detector_image.py](isofor_test_anomaly_detector_image.py) is the inference code to determine anomaly data from anomalous image.It can generate anomaly score frame by frame.
