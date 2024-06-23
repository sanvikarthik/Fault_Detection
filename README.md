<<<<<<< HEAD
# Fault Detection in Pneumatic Systems

 ![TimeGAN](https://img.icons8.com/color/48/000000/time.png)
 ![MATLAB](https://img.icons8.com/color/48/000000/matlab.png)
 ![Python](https://img.icons8.com/color/48/000000/python.png)
 
## Overview
This project focuses on developing a fault detection system for pneumatic systems using TimeGAN (Time-series Generative Adversarial Network) for data generation and analysis.
 MATLAB and Python are integrated to implement machine learning algorithms and data preprocessing tasks.

## Features

![TimeGAN](https://img.icons8.com/color/48/000000/time.png)
### TimeGAN Model: 
Generates synthetic time-series data crucial for training the fault detection model.

![MATLAB](https://img.icons8.com/color/48/000000/matlab.png)
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
=======
# Fault_Detection
Fault Detection in Pneumatic Systems:

Fault detection in pneumatic systems for predictive maintenance involves using data-driven approaches to identify anomalies or deviations from normal operation. This proactive approach helps prevent unexpected breakdowns and reduces maintenance costs by allowing timely interventions based on predictive insights.

Steps in Fault Detection for Predictive Maintenance:
Data Collection: Gather sensor data from pneumatic systems, including pressure, temperature, flow rates, valve positions, etc. This data is typically time-series in nature and can be collected continuously or at regular intervals.

Preprocessing: Clean the data by handling missing values, removing outliers, and ensuring consistency in data format and scale. This step is crucial for accurate analysis and model training.

Feature Engineering: Extract relevant features from raw sensor data that can indicate system health or potential faults. Features may include statistical metrics (mean, variance), frequency domain features (using FFT), and derived features based on domain knowledge.

Fault Detection Models:

Statistical Models: Use statistical techniques (e.g., PCA, Autoencoders) to detect anomalies by comparing observed data with expected behavior.
Machine Learning Models: Train supervised or unsupervised models (e.g., SVM, Isolation Forest) on labeled or unlabeled data to classify normal and abnormal states.
Time Series Models: Apply techniques like LSTM (Long Short-Term Memory) or GRU (Gated Recurrent Unit) for sequential data to capture temporal dependencies in sensor readings.
Synthetic Data Generation:

Singular Value Decomposition (SVD): Reduce the dimensionality of high-dimensional sensor data using SVD. This helps in capturing essential patterns and features while discarding noise and redundancy, aiding in anomaly detection.
TimeGAN (Time-series Generative Adversarial Network): Generate synthetic time-series data that mimic the statistical characteristics of real sensor data. TimeGAN uses adversarial training to learn the data distribution and generate realistic synthetic samples, which can augment the limited real-world data for training fault detection models.
Training and Evaluation:

Model Training: Train fault detection models using both real and synthetic data. Real data helps capture actual system behaviors, while synthetic data enhances model robustness by diversifying training samples.
Evaluation: Validate models using metrics like accuracy, precision, recall, and F1-score. Assess the model's ability to detect faults accurately and timely.
Deployment and Monitoring: Deploy trained models in production environments to continuously monitor pneumatic systems. Integrate with maintenance schedules to trigger alerts or actions when anomalies or potential faults are detected.

TimeGAN.txt contains details about TimeGAN code implementation and details.
SingularValurDecomposition.txt contains information about SVD implementation.

The above methods have been used to generate artificial/Synthetic data for pneumatic systems.

Testing, Training, and Validation sets contains cleaned data of pneumatic systems for predictive maint


>>>>>>> ed39362ed5fbce04434bcbf01b5f3113fe45b6cf
