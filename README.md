# Fault Detection in Pneumatic Systems

 ![TimeGAN](https://img.icons8.com/color/48/000000/time.png)
![MATLAB](https://skillicons.dev/icons?i=matlab)
 ![Python](https://img.icons8.com/color/48/000000/python.png)
 
## Overview
This project focuses on developing a fault detection system for pneumatic systems using TimeGAN (Time-series Generative Adversarial Network) for data generation and analysis.
 MATLAB and Python are integrated to implement machine learning algorithms and data preprocessing tasks.
Fault detection in pneumatic systems for predictive maintenance involves using data-driven approaches to identify anomalies or deviations from normal operation. This proactive approach helps prevent unexpected breakdowns and reduces maintenance costs by allowing timely interventions based on predictive insights.


## Features

![TimeGAN](https://img.icons8.com/color/48/000000/time.png)
### TimeGAN Model: 
Generates synthetic time-series data crucial for training the fault detection model.

![MATLAB](https://skillicons.dev/icons?i=matlab)
### MATLAB Integration: 
Utilizes MATLAB for specific algorithm implementations and analysis.

![Python](https://img.icons8.com/color/48/000000/python.png)
### Python Libraries: 
Employs essential Python libraries for data manipulation and machine learning tasks:

![NumPy](https://img.icons8.com/color/48/000000/numpy.png)
#### NumPy 
Provides support for large, multi-dimensional arrays and matrices.

![pandas](https://img.icons8.com/color/48/000000/pandas.png)
#### pandas 
Offers data structures and data analysis tools for easy data handling.

![scikit-learn](https://img.icons8.com/color/48/000000/python.png)
#### scikit-learn 
 Provides simple and efficient tools for data mining and data analysis.

![TensorFlow](https://img.icons8.com/color/48/000000/tensorflow.png)
#### TensorFlow 
 An open-source machine learning framework for dataflow and differentiable programming across a range of tasks.

#### MinMaxScaler 
From scikit-learn, scales features to a specified range, often [0, 1].

## Installation
To set up the project locally, follow these steps:

### Clone the repository:


```console
git clone https://github.com/sanvikarthik/Fault_Detection.git
cd Fault_Detection
```
Install dependencies:


```python
pip install -r requirements.txt
```
## Usage
Generating Synthetic Data
Use the TimeGAN model to generate synthetic time-series data.

## Contributors
Ritheesh R M

Anirudh K N 

Divyesh Reddy 

Srinikethan 

Sanvi Karthik 


## Steps 
### Data Collection:
 Gather sensor data from pneumatic systems, including pressure, temperature, flow rates, valve positions, etc. This data is typically time-series in nature and can be collected continuously or at regular intervals.

### Preprocessing: 
Clean the data by handling missing values, removing outliers, and ensuring consistency in data format and scale. This step is crucial for accurate analysis and model training.

### Feature Engineering: 
Extract relevant features from raw sensor data that can indicate system health or potential faults. Features may include statistical metrics (mean, variance), frequency domain features (using FFT), and derived features based on domain knowledge.




