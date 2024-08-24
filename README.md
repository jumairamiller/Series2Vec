# Series2Vec
This is a PyTorch implementation of
**Series2Vec: Similarity-based Self-supervised Representation Learning for Time Series Classification**.
### Code Update: [22.03.2024]
#### Note:
If you downloaded the code prior to the latest update, please ensure to update to the current version as it is consistent with the paper.

<p align="center">
    <img src="Fig/Series2Vec_01.png">
</p> 

### Get data from UEA Archive and HAR and Ford Challenge
Download dataset files and place them into the specified folder
UEA: [Here](https://www.timeseriesclassification.com/aeon-toolkit/Archives/Multivariate2018_ts.zip)

Copy the datasets folder to: Datasets/UEA/

## Setup

_Instructions refer to Ubuntu Linux System, this is a strict requirement for the code, as well as an NVIDIA GPU enabled machine as Cuda is required for the project

This code has been tested with `Python 3.7`(by original author Navid Foumani) and `3.8`(by original author and myself).

`pip install -r requirements.txt'
NOTE: some dependencies are specific to ubuntu and therefore are commented out within requirements.txt and need to be manually installed using apt-get or apt

## Run

