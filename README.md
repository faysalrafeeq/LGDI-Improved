# Codebase for "Improved LGDI algorithm "
# This directory contains implementations of the LGDI framework for imputation
# using traffic volume dataset from Kaggle.

# Paper and Authors: 
R. Wu, S. D. Hamshaw, L. Yang, D. W. Kincaid, R. Etheridge and A. Ghasemkhani, 
"Data Imputation for Multivariate Time Series Sensor Data With Large Gaps of Missing Data,
"in IEEE Sensors Journal, vol. 22, no. 11, pp. 10671-10683, 
June 1, 2022.
 
# Paper Link: doi: 10.1109/JSEN.2022.3166643.

#  DataSource:
- Kaggle (https://www.kaggle.com/datasets/mikedev/metro-traffic-volume)


# Running the repo
1). Make sure you have anaconda installed. It already has a virtual environment inside it. We only need to create one.


2). Create a virtual environment:
python3 -m venv python_venv


3). Activate the virtual environment:
source python_venv/bin/activate

4). To download the dependencies from the environment :
    4.1) pip3 install -r requirements.txt
    4.2) conda env create -f environment.yml ( From Conda)


5). Run jupyter notebook command.
Jupiter-notebook


6). Every algorithm is in a separate file.
