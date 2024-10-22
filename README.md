# Anomaly Detection in Network Traffic Scenarios Using ML-Based Algorithms

## Project Overview

This project focuses on developing machine learning-based algorithms to detect anomalies in different network traffic scenarios. Identifying malicious behavior or unusual patterns is critical for maintaining network security and operational efficiency. Traditional anomaly detection methods struggle with accuracy due to the complexity of modern networks. This project leverages supervised learning models like logistic regression, random forest, and regression to accurately detect traffic anomalies in various scenarios. Simulations are conducted using OMNeT++ or Sionna, and machine learning models are integrated to classify abnormal behaviors.

## Objectives

1. **Data Collection**: Gather data from simulations in OMNeT++ or Sionna, and use pre-existing datasets. Data augmentation methods may also be employed to ensure the models are well-trained.
2. **Algorithm Development**: Implement supervised learning algorithms such as logistic regression, random forest, and decision trees to detect network anomalies.
3. **Simulation**: Use OMNeT++ or Sionna to simulate different network traffic scenarios, including Distributed Denial of Service (DDoS) attacks, spoofing, and congestion.
4. **Model Evaluation**: Evaluate the performance of the developed algorithms based on metrics like accuracy, false positive rate, and computational efficiency.

## Methodology

1. **Literature Review**: A thorough review of existing methods and technologies in network traffic anomaly detection.
2. **Simulation Environment**: Simulate normal and anomalous network traffic patterns in OMNeT++ or Sionna.
3. **Data Collection**: Extract relevant traffic features like packet size, flow duration, and throughput for use in training the models.
4. **ML-Based Algorithms**: Supervised learning models like logistic regression, random forest, and decision trees will be trained to identify anomalies.
5. **Performance Evaluation**: Assess performance indicators such as packet delivery ratio, delay, throughput, and adaptability to real-time conditions.

## Tools and Technologies

- **OMNeT++**: A discrete event simulator for simulating network traffic.
- **Sionna**: A library for machine learning research in wireless communications.
- **Python**: For developing and integrating AI algorithms.
- **AI Frameworks**: Used for training and deploying machine learning models.

## Expected Outcomes

- A robust anomaly detection system that integrates ML-based algorithms into OMNeT++ or Sionna.
- Accurate detection of network traffic anomalies with minimal false positives and high precision.
- Comprehensive evaluation comparing the performance of various ML models.

## References

- OMNeT++: https://omnetpp.org
- Sionna: https://nvlabs.github.io/sionna/
- OMNeT++ Simulation Manual: https://doc.omnetpp.org/omnetpp/SimulationManual.pdf
- Deep Learning for Network Traffic Anomaly Detection (IEEE Access): https://doi.org/10.1109/ACCESS.2021.3052369
