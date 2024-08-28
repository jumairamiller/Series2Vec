# Series2Vec
This is a PyTorch implementation of
**Series2Vec: Similarity-based Self-supervised Representation Learning for Time Series Classification**.
### Code Update: [22.03.2024]
#### Note:
If you downloaded the code prior to the latest update, please ensure to update to the current version as it is consistent with the paper.

<p align="center">
    <img src="Fig/Series2Vec_01.png">
</p> 

### Get data from UEA Archive 
Download dataset files and place them into the specified folder
UEA: [Here](https://www.timeseriesclassification.com/aeon-toolkit/Archives/Multivariate2018_ts.zip)

Copy the datasets folder to: Datasets/UEA/

## Setup

_Instructions refer to Ubuntu Linux System, this is a strict requirement for the code, as well as an NVIDIA GPU enabled machine as Cuda is required for the project

This code has been tested with `Python 3.7`(by original author Navid Foumani) and `3.8`(by original author and myself).

Optional step) to create and activate a virtual environment before installing required rependencies, run the following commands:

            python3 -m venv series2vec_env
            source series2vec_env/bin/activate
            
To install required dependencies, run the following command:

            pip install -r requirements.txt
            
NOTE: some dependencies are specific to ubuntu and therefore are commented out within requirements.txt and need to be manually installed using apt-get or apt

## Run


Step 1) cd to 'Series2Vec' using terminal
Step 2) Run the following command to execute Series2Vec on the UEA datasets: 

            python main.py --dataset UEA --output_dir Results
            
NOTE: more parameters for execution can be found in args.py; Run output will be stored in Series2Vec/Results/

