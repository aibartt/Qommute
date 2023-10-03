# Qommute


## Technical challenge

_Create a program that applies one or more quantum algorithms to address a sustainability challenge._


## Introduction
Welcome to the *Qommute* - Quantum Routing and Placement Project! This project aims to tackle the challenging task of optimizing bus station placements and routing using a combination of quantum computing and machine learning. By leveraging cutting-edge technologies, we aim to revolutionize public transportation systems for greater efficiency and reduced delays.

## Table of Contents
- [Qommute](#qommute)
  - [Introduction](#introduction)
  - [Table of Contents](#table-of-contents)
  - [Getting Started](#getting-started)
  - [Features](#features)
  - [Quantum Placement](#quantum-placement)
  - [Machine Learning Model](#machine-learning-model)
  - [Optimum Routing](#optimum-routing)
  - [Visualization](#visualization)
  - [Prerequisites](#prerequisites)
  - [Acknowledgements](#acknowledgements)

## Getting Started
To run this project locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies as listed in the [Prerequisites](#prerequisites) section.
4. Use the provided guide to run quantum placement, machine learning predictions, and routing calculations.
5. Explore the interactive visualization to interpret the results.

## Features
- Quantum placement optimization: Find the optimal bus station placements using quantum algorithms.
- Machine learning-based delay prediction: Predict delays using machine learning models trained on historical data.
- Optimum routing calculation: Determine the best routes considering quantum placement and delay predictions.
- Interactive visualization of results: Visualize the optimized placements, predicted delays, and optimum routing on a user-friendly interface.

## Quantum Placement
In the quantum placement component, we utilize quantum computing to search for the best locations for bus stations. We employ quantum algorithms and libraries like Qiskit to optimize the placement for minimal travel times and passenger convenience.

## Machine Learning Model
Our machine learning model predicts delays in the transportation system. It is trained on a comprehensive dataset of time of the year, category of transportation, previous delays, history of delays, category and subcategory of delays such as crew availability, infrastructure, police and medical, operating conditions, planned ROW works and so forth. The model architecture, dataset details, and training process can be found in the project's documentation.

## Optimum Routing
The optimum routing component combines the results from quantum placement and the machine learning model. By factoring in both optimized placement and predicted delays, we calculate the most efficient routes for buses to minimize delays and enhance the overall transportation system.

## Visualization
Our project offers an intuitive visualization tool to interactively explore the optimized placements and routing results. Check out the project's presentation for detailed information.

## Prerequisites
The project has the following prerequisites:

- Python 3.7 or higher
- Qiskit for quantum computing
- PyTorch for machine learning


## Acknowledgements

**Code Devs:** [Samyam Lamichhane](https://github.com/declansam), [Sarthak Malla](https://github.com/Sarthak-Malla), [Sasha Malik](https://github.com/Sasha-Malik)   
**Contributors**: Andy Lee, Erik Lee, Josh Handelman 

This project was created at the [2023 Tandon hAQathon](https://wp.nyu.edu/haqathon/) to address a sustainability challenge to solve using quantum computation.  
