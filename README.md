# stratosphere_ml_challenge

# Objective
- Provide Python scripts and/or a Python Jupyter notebook with the data analysis and a machine-learning model of the given network traffic dataset. 

# Additional information
- We are providing you with a directory of Zeek log files that were extracted from a packet capture of a Remote Access Trojan (RAT) running on an infected mobile phone.
- The Zeek log files contain both benign and malicious traffic.
- The files contain no labels, but the first 4 minutes of the traffic are benign. After the first 4 minutes, the traffic is unknown. This information can be used to label the traffic.
- **Goal**: To develop a machine learning model that is trained and evaluated on this data and that can separate the malware traffic from the normal traffic.
- The main idea behind this challenge is to evaluate your thought process through the different steps of creating a machine learning pipeline: goal setting, data analysis, data preprocessing, modeling, reporting, etc. It is not necessary that the final model has great performance, we are aware that the dataset is very small.


# Installation
```bash
git clone https://github.com/JakubTehlar/stratosphere_ml_challenge

# Create an environment
python3 -m venv .venv

# Activate the environment
source .venv/bin/activate

python3 -m pip install -U pip
python3 -m pip install ipykernel
python3 -m ipykernel install --user --name ml_chall --display-name 'Python (ML challenge)'

# Install requirements
pip install -r requirements.txt
```
