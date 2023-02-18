# Diagnosing Heart Disease
- Authors: Hanzhang Cao, Karlie Truong, Kaylie Nguyen, Ser Jie Ng
- Contributors: Hanzhang Cao, Matthias Kammueller, Nicole White

## About
The project is developed upon the dsci100 term project by the contributors listed above. Permission to reuse the data analysis has been given by all contributors. We aim to determine: Based on only two predictors gathered from health checkups performed by doctors, does somebody suffer from heart disease?

To answer this question, we analyze the Cleveland data file from https://archive.ics.uci.edu/ml/datasets/Heart+Disease, containing data collected by Robert Detrano at the V.A. Medical Center, Long Beach and Cleveland Clinic Foundation in 1988. This dataset contains 303 instances. 

We attempt to build a classification model using the K-nearest neighbour algorithm to predict heart disease diagnosis. Our model offers a preliminary diagnosis based 2 symptoms. This can save medical costs for patients who are properly diagnosed with heart disease by our model as well as diagnostic time. 

## Team work Contract
Team work contract for group 03 is found in the README.md file in commit ba459c1 (https://github.com/karlie-tr/dsci-310-group-03/tree/ba459c1340d4a1efffd9a90d9d0eecddbd498a81)

## Report
The data analysis report can be found [here] (https://github.com/karlie-tr/dsci-310-group-03/blob/1c9dee99b0c500339d5705034ac46a6c5b25daaa/heart_disease_classification.ipynb)

## Usage
To maintain the reproducibility of this project, we use Docker container images to create the same computational environment that the project was created on. In order to run our analysis, please follow the steps listed below:
1. Create an account and install DockerHub following the instruction [here] (https://docs.docker.com/get-docker/)
2. In your terminal, navigate to the folder where you want to store the project then clone it project into your local computer 
    'git clone https://github.com/karlie-tr/dsci-310-group-03.git'
3. In your terminal, pull the lastest version of the Docker image
    'docker pull karlietr/dsci-310-group-03:latest'
4. To run the analysis from the Docker container:
    - In terminal:
    'docker run --r--user root -v $(pwd):/home/jovyan/work -p 8888:8888 dsci-310-group-03:latest'
    - In Jupyter: navigate to heart_disease_classification.ipynb then select 'Kernel > Restart Kernel and Run All Cells...'


## Dependencies
|Package | Version |
|--------|---------|
|R|4.1.3|
|tidyverse |1.3.2|
|repr|1.1.6|
|tidymodels|1.0.0|
|RColorBrewer|1.1-3|
|cowplot|1.1.1|

## License Information
Our project uses the MIT open source license.


