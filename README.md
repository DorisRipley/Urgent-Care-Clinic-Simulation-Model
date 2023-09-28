# Urgent Care Clinic Simulation Model

This repository contains a simulation model of an Urgent Care (UC) clinic, simulating patient flow, service processes, waiting times, and balking probabilities. The UC clinic has three doctors and one nurse to serve patients, categorized as high-priority and low-priority based on their health conditions.

## Table of Contents
Introduction
Features
Simulation Process
Results and Recommendations
Dependencies
Usage
Contribution

## Introduction
This project aims to simulate the operational dynamics of an Urgent Care clinic to understand and optimize patient flow times and analyze the balking behavior of low-priority patients.

## Features
Patient Arrival & Triage
Priority-Based Service Process
Balking and Reneging Analysis
Performance Metrics Calculation

## Simulation Process
Patients arrive at the UC clinic with interarrival times following an exponential distribution. They are then triaged by a nurse and categorized into high-priority and low-priority, with service time for triage distributed by a triangular distribution.

The patients wait in a common waiting area and doctors attend to them based on a first-come-first-served basis. Low-priority patients have a possibility to balk if their waiting time exceeds a predetermined threshold.

For more details on the simulation process and logic, refer to the code documentation provided within the project files.

## Results and Recommendations
Based on the simulation results, several operational insights are derived, and recommendations are made to improve the efficiency and patient experience at the Urgent Care clinic. The results focus on average flow times for different priority patients and the balking probability for low-priority patients.

Detailed results and recommendations can be found in the Results and Recommendations section.

**Dependencies**

R (>= 3.6.1)
triangle
simmer
Usage
To run the simulation model, clone this repository to your local machine and execute the provided R script. Modify the parameters and configurations as per your requirements and analysis needs. Ensure that all the dependencies are installed.

**Contribution**

Contributions are welcome! If you wish to contribute, please create a new branch, make your changes, and submit a pull request. For major changes, please open an issue first to discuss the proposed change.

This project is open-source and available to everyone for research and development purposes. Please make sure to reference this repository if you are using the code or the model for your projects or research.

Thank you for exploring this Urgent Care Clinic Simulation Model!
