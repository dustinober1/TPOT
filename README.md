# TPOT

This repository contains a project that utilizes TPOT, a Python Automated Machine Learning tool that optimizes machine learning pipelines using genetic programming. TPOT is designed to find the best machine learning pipeline for your data by exploring various models and feature engineering steps.

## Table of Contents

- [Overview](#overview)
- [Project - TPOT IRIS](#project---tpot-iris)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

TPOT (Tree-based Pipeline Optimization Tool) is an automated machine learning (AutoML) tool that uses genetic algorithms to optimize machine learning pipelines. This repository demonstrates how to use TPOT to find the optimal pipeline for the popular IRIS dataset, a classic dataset used for classification tasks.

## Project - TPOT IRIS

The `TPOT IRIS` project applies TPOT to the IRIS dataset to automate the process of machine learning model selection and hyperparameter tuning. The goal is to identify the best possible model pipeline for classifying the different species of the IRIS flower based on its features.

### Directory Structure

- **TPOT IRIS/**: Contains the TPOT analysis and related files for the IRIS dataset.

[Project Content](https://github.com/dustinober1/TPOT/tree/main/TPOT%20IRIS)

## Installation

To run the code in this repository, you need to install Python and the required libraries.

1. **Clone the repository**:

    ```bash
    git clone https://github.com/dustinober1/TPOT.git
    cd TPOT
    ```

2. **Install the required dependencies**:

    TPOT and other dependencies can be installed using pip:

    ```bash
    pip install tpot pandas scikit-learn
    ```

## Usage

To run the TPOT pipeline optimization for the IRIS dataset, navigate to the `TPOT IRIS` directory and execute the Python script:

```bash
cd TPOT\ IRIS
python tpot_iris.py
```
The script will automatically run TPOT on the IRIS dataset, generate various models, and provide the best-performing pipeline as output. It will also save the generated Python code for the best pipeline, allowing you to use it directly in your projects.

## Contributing

Contributions are welcome! If you have ideas for improvements, new datasets to analyze, or new ways to utilize TPOT, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
