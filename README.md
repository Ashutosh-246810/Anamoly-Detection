# Anomaly Detection in Network Traffic using Isolation Forest

This project applies the Isolation Forest algorithm to detect anomalies in network traffic data using the KDD Cup 1999 dataset. It demonstrates an unsupervised machine learning approach to intrusion detection.

## Dataset: KDD Cup 1999

The KDD Cup 1999 dataset is a standard benchmark for evaluating network intrusion detection systems. It includes a wide range of simulated attacks and normal connections.

- Total records: ~5 million (we use the 10% subset for efficiency)
- Features: 41 (continuous, discrete, and symbolic)
- Labels: 22 attack types + normal traffic

Download link: [KDD Cup 1999 Data](# Anomaly Detection in Network Traffic using Isolation Forest

This project applies the Isolation Forest algorithm to detect anomalies in network traffic data using the KDD Cup 1999 dataset. It demonstrates an unsupervised machine learning approach to intrusion detection.

## Dataset: KDD Cup 1999

The KDD Cup 1999 dataset is a standard benchmark for evaluating network intrusion detection systems. It includes a wide range of simulated attacks and normal connections.

- Total records: ~5 million (we use the 10% subset for efficiency)
- Features: 41 (continuous, discrete, and symbolic)
- Labels: 22 attack types + normal traffic

Download link: [KDD Cup 1999 Data](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)

## Model: Isolation Forest

Isolation Forest is an efficient, tree-based anomaly detection method. It works by randomly partitioning the data and isolating outliers that require fewer partitions.

### Advantages

- Suitable for high-dimensional data
- Requires no labeled training data
- Scales well to large datasets

## Project Workflow

1. Load and sample the KDD dataset
2. Preprocess the data
   - Encode categorical features
   - Normalize numeric features
3. Train an Isolation Forest model
4. Predict anomalies
5. Evaluate the results using metrics and visualizations


